.. java:import:: org.motechproject.security.domain MotechSecurityConfiguration

.. java:import:: org.motechproject.security.model SecurityConfigDto

.. java:import:: org.motechproject.security.service MotechURLSecurityService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

SecurityRulesController
=======================

.. java:package:: org.motechproject.security.web.controllers
   :noindex:

.. java:type:: @Controller public class SecurityRulesController

   Class for CRUD operations on security rule configuration. Also provides a status method for testing purposes.

Methods
-------
getSecurityRules
^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public SecurityConfigDto getSecurityRules()
   :outertype: SecurityRulesController

securityStatus
^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public String securityStatus()
   :outertype: SecurityRulesController

updateSecurityRules
^^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void updateSecurityRules(SecurityConfigDto securityConfig)
   :outertype: SecurityRulesController

