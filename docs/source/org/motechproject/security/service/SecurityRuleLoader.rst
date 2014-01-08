.. java:import:: com.google.gson.reflect TypeToken

.. java:import:: org.motechproject.commons.api.json MotechJsonReader

.. java:import:: org.motechproject.security.domain MotechSecurityConfiguration

.. java:import:: org.motechproject.security.domain MotechURLSecurityRule

.. java:import:: org.motechproject.security.repository AllMotechSecurityRules

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.context ApplicationContext

.. java:import:: org.springframework.core.io Resource

.. java:import:: org.springframework.stereotype Component

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.util List

SecurityRuleLoader
==================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: @Component public class SecurityRuleLoader

   Helper class that scans an application context for security rules and re-initializes the MotechProxyManager security chain.

Methods
-------
loadRules
^^^^^^^^^

.. java:method:: public synchronized void loadRules(ApplicationContext applicationContext)
   :outertype: SecurityRuleLoader

   Attempts to load rules from the application context, if rules are found, the security configuration is updated. Synchronized so there are not race conditions on the data.

