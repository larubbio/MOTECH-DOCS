.. java:import:: java.util List

.. java:import:: org.motechproject.security.domain MotechSecurityConfiguration

.. java:import:: org.motechproject.security.domain MotechURLSecurityRule

.. java:import:: org.springframework.security.access.prepost PreAuthorize

MotechURLSecurityService
========================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: public interface MotechURLSecurityService

   Service to access and update security configuration details from the platform. Permission based, method level security is defined to prevent unauthorized users from updating security.

Methods
-------
findAllSecurityRules
^^^^^^^^^^^^^^^^^^^^

.. java:method:: @PreAuthorize  List<MotechURLSecurityRule> findAllSecurityRules()
   :outertype: MotechURLSecurityService

   A protected method for viewing security rule information for the platform.

   :return: All URL security rules found in the database

updateSecurityConfiguration
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @PreAuthorize  void updateSecurityConfiguration(MotechSecurityConfiguration configuration)
   :outertype: MotechURLSecurityService

   A protected method for updating security configuration for the platform.

   :param configuration: The updated security information, which will cause an updating of the motech proxy manager

