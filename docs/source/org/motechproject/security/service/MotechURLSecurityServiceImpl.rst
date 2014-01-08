.. java:import:: org.motechproject.security.domain MotechSecurityConfiguration

.. java:import:: org.motechproject.security.domain MotechURLSecurityRule

.. java:import:: org.motechproject.security.repository AllMotechSecurityRules

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util List

MotechURLSecurityServiceImpl
============================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: @Service public class MotechURLSecurityServiceImpl implements MotechURLSecurityService

Methods
-------
findAllSecurityRules
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public List<MotechURLSecurityRule> findAllSecurityRules()
   :outertype: MotechURLSecurityServiceImpl

updateSecurityConfiguration
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public void updateSecurityConfiguration(MotechSecurityConfiguration configuration)
   :outertype: MotechURLSecurityServiceImpl

