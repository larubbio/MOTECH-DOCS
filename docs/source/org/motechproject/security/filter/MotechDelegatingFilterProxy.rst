.. java:import:: org.motechproject.security.model PermissionDto

.. java:import:: org.motechproject.security.service MotechPermissionService

.. java:import:: org.motechproject.security.service MotechProxyManager

.. java:import:: org.springframework.security.core GrantedAuthority

.. java:import:: org.springframework.security.core.context SecurityContextHolder

.. java:import:: org.springframework.security.web.authentication AnonymousAuthenticationFilter

.. java:import:: org.springframework.web.context WebApplicationContext

.. java:import:: org.springframework.web.filter DelegatingFilterProxy

.. java:import:: javax.servlet Filter

.. java:import:: javax.servlet FilterChain

.. java:import:: javax.servlet ServletException

.. java:import:: javax.servlet ServletRequest

.. java:import:: javax.servlet ServletResponse

.. java:import:: java.io File

.. java:import:: java.io FileInputStream

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.io InputStreamReader

.. java:import:: java.util ArrayList

.. java:import:: java.util List

.. java:import:: java.util Properties

MotechDelegatingFilterProxy
===========================

.. java:package:: org.motechproject.security.filter
   :noindex:

.. java:type:: public class MotechDelegatingFilterProxy extends DelegatingFilterProxy

   A custom delegating filter that determines whether the platform is in admin mode or not. When filtering, if the MotechProxyManager has been set, it will delegate to that instead of the delegate from its superclass. The original delegate is the original security chain created from the securityContext. By instead delegating to the MotechProxyManager, the filter chain can be dynamically updated and all requests re-directed to that chain.

Constructors
------------
MotechDelegatingFilterProxy
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechDelegatingFilterProxy(String targetBeanName, WebApplicationContext wac)
   :outertype: MotechDelegatingFilterProxy

Methods
-------
doFilter
^^^^^^^^

.. java:method:: @Override public void doFilter(ServletRequest request, ServletResponse response, FilterChain filterChain) throws ServletException, IOException
   :outertype: MotechDelegatingFilterProxy

   If the proxy manager is available, filtering should be instead delegated to its FilterChainProxy.

