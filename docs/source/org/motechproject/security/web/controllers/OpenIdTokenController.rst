.. java:import:: org.motechproject.security.service PasswordRecoveryService

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation RequestParam

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io IOException

OpenIdTokenController
=====================

.. java:package:: org.motechproject.security.web.controllers
   :noindex:

.. java:type:: @Controller public class OpenIdTokenController

Methods
-------
resetView
^^^^^^^^^

.. java:method:: @RequestMapping public void resetView(String token, HttpServletRequest request, HttpServletResponse response)
   :outertype: OpenIdTokenController

