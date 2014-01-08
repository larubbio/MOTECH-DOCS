.. java:import:: org.motechproject.security.model PermissionDto

.. java:import:: org.motechproject.security.service MotechPermissionService

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans BeansException

.. java:import:: org.springframework.beans.factory.config BeanPostProcessor

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: org.springframework.expression ExpressionParser

.. java:import:: org.springframework.expression.spel SpelNode

.. java:import:: org.springframework.expression.spel.standard SpelExpression

.. java:import:: org.springframework.security.access.expression.method DefaultMethodSecurityExpressionHandler

.. java:import:: org.springframework.security.access.prepost PostAuthorize

.. java:import:: org.springframework.security.access.prepost PreAuthorize

.. java:import:: java.lang.reflect Method

.. java:import:: java.util ArrayList

.. java:import:: java.util List

SecurityAnnotationBeanPostProcessor
===================================

.. java:package:: org.motechproject.security.annotations
   :noindex:

.. java:type:: public class SecurityAnnotationBeanPostProcessor implements BeanPostProcessor

   A \ :java:ref:`BeanPostProcessor`\  used by Motech to load permissions from modules. Given a module context, it looks for \ :java:ref:`PreAuthorize`\  and \ :java:ref:`PostAuthorize`\  annotations. These annotations are then parsed using an \ :java:ref:`ExpressionParser`\ . The permission names are deduced from \ ``hasRole``\  and \ ``hasAnyRole``\  in the annotation value. The names of permissions are then saved using the \ :java:ref:`MotechPermissionService`\ . The bundle name used to construct the permission is retrieved from the application context.

Constructors
------------
SecurityAnnotationBeanPostProcessor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public SecurityAnnotationBeanPostProcessor(MotechPermissionService permissionService)
   :outertype: SecurityAnnotationBeanPostProcessor

Methods
-------
postProcessAfterInitialization
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Object postProcessAfterInitialization(Object bean, String beanName) throws BeansException
   :outertype: SecurityAnnotationBeanPostProcessor

postProcessBeforeInitialization
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public Object postProcessBeforeInitialization(Object bean, String beanName) throws BeansException
   :outertype: SecurityAnnotationBeanPostProcessor

processAnnotations
^^^^^^^^^^^^^^^^^^

.. java:method:: public void processAnnotations(ApplicationContext applicationContext)
   :outertype: SecurityAnnotationBeanPostProcessor

