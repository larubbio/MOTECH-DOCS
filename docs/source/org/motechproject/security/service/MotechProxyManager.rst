.. java:import:: org.motechproject.commons.api MotechException

.. java:import:: org.motechproject.commons.api.json MotechJsonReader

.. java:import:: org.motechproject.security.builder SecurityRuleBuilder

.. java:import:: org.motechproject.security.domain MotechSecurityConfiguration

.. java:import:: org.motechproject.security.domain MotechURLSecurityRule

.. java:import:: org.motechproject.security.repository AllMotechSecurityRules

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.web FilterChainProxy

.. java:import:: org.springframework.security.web SecurityFilterChain

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.util ArrayList

.. java:import:: java.util Comparator

.. java:import:: java.util List

.. java:import:: java.util TreeSet

MotechProxyManager
==================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: @Component public class MotechProxyManager

   The MotechProxyManager acts as a wrapper around Spring's FilterChainProxy. The FilterChainProxy contains a list of immutable SecurityFilterChain objects which Spring's security consults for filters when handling requests. In order to dynamically define new secure, a new FilterChainProxy is constructed and the reference is updated. The MotechProxyManager acts as a customized delegate in MotechDelegatingFilterProxy.

Methods
-------
getFilterChainProxy
^^^^^^^^^^^^^^^^^^^

.. java:method:: public FilterChainProxy getFilterChainProxy()
   :outertype: MotechProxyManager

initializeProxyChain
^^^^^^^^^^^^^^^^^^^^

.. java:method:: public void initializeProxyChain()
   :outertype: MotechProxyManager

   This method serves the same purpose of rebuildProxyChain, but does not require any kind of security authentication so it should only ever be used by the activator, which does not have an authentication object.

rebuildProxyChain
^^^^^^^^^^^^^^^^^

.. java:method:: public synchronized void rebuildProxyChain()
   :outertype: MotechProxyManager

   Method to invoke to dynamically re-define the Spring security. All rules converted into security filter chains in order to create a new FilterChainProxy. The order of the rules in the list matters for filtering purposes.

setFilterChainProxy
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setFilterChainProxy(FilterChainProxy proxy)
   :outertype: MotechProxyManager

