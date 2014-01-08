.. java:import:: java.util List

.. java:import:: org.motechproject.security.domain MotechSecurityConfiguration

.. java:import:: org.motechproject.security.domain MotechURLSecurityRule

AllMotechSecurityRules
======================

.. java:package:: org.motechproject.security.repository
   :noindex:

.. java:type:: public interface AllMotechSecurityRules

   Repository for crud operations related to Motech security config.

Methods
-------
addOrUpdate
^^^^^^^^^^^

.. java:method::  void addOrUpdate(MotechSecurityConfiguration securityConfig)
   :outertype: AllMotechSecurityRules

   Add or update the MOTECH security configuration rules

   :param securityConfig: The security config for MOTECH

getMotechSecurityConfiguration
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method::  MotechSecurityConfiguration getMotechSecurityConfiguration()
   :outertype: AllMotechSecurityRules

   Returns the full security configuration

   :return: The full MOTECH security configuration

getRules
^^^^^^^^

.. java:method::  List<MotechURLSecurityRule> getRules()
   :outertype: AllMotechSecurityRules

   Convenience method for retrieving all of the individual security rules from the security configuration.

   :return: A list of all URL pattern security rules from the database

getRulesByOrigin
^^^^^^^^^^^^^^^^

.. java:method::  List<MotechURLSecurityRule> getRulesByOrigin(String origin)
   :outertype: AllMotechSecurityRules

remove
^^^^^^

.. java:method::  void remove(MotechSecurityConfiguration config)
   :outertype: AllMotechSecurityRules

   Remove the existing security configuration

   :param config: The security configuration to remove

