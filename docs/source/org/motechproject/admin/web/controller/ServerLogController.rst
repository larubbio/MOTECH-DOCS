.. java:import:: org.apache.commons.io FileUtils

.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.motechproject.osgi.web.domain LogMapping

.. java:import:: org.motechproject.osgi.web.service ServerLogService

.. java:import:: org.motechproject.osgi.web.settings Loggers

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.stereotype Controller

.. java:import:: org.springframework.web.bind.annotation RequestBody

.. java:import:: org.springframework.web.bind.annotation RequestMapping

.. java:import:: org.springframework.web.bind.annotation RequestMethod

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.io File

.. java:import:: java.io FileInputStream

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.io PrintWriter

.. java:import:: java.util List

ServerLogController
===================

.. java:package:: org.motechproject.admin.web.controller
   :noindex:

.. java:type:: @Controller public class ServerLogController

Constructors
------------
ServerLogController
^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public ServerLogController(ServerLogService logService)
   :outertype: ServerLogController

Methods
-------
changeLogLevels
^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseStatus public void changeLogLevels(Loggers config)
   :outertype: ServerLogController

getEntireServerLog
^^^^^^^^^^^^^^^^^^

.. java:method:: @RequestMapping public void getEntireServerLog(HttpServletResponse response) throws IOException
   :outertype: ServerLogController

getLogLevels
^^^^^^^^^^^^

.. java:method:: @RequestMapping @ResponseBody public Loggers getLogLevels()
   :outertype: ServerLogController

getServerLog
^^^^^^^^^^^^

.. java:method:: @RequestMapping public void getServerLog(HttpServletResponse response) throws IOException
   :outertype: ServerLogController

