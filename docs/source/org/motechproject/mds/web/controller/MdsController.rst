.. java:import:: org.motechproject.mds.ex MdsException

.. java:import:: org.motechproject.mds.web ExampleData

.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.web.bind.annotation ExceptionHandler

.. java:import:: org.springframework.web.bind.annotation ResponseBody

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

.. java:import:: java.io IOException

MdsController
=============

.. java:package:: org.motechproject.mds.web.controller
   :noindex:

.. java:type:: public abstract class MdsController

   The \ ``MdsController``\  is a basic controller for other controllers defined in the mds module. Its function is to handle all \ :java:ref:`org.motechproject.mds.ex.MdsException`\  exceptions from extended classes.

Methods
-------
getExampleData
^^^^^^^^^^^^^^

.. java:method:: protected static ExampleData getExampleData()
   :outertype: MdsController

handleMdsException
^^^^^^^^^^^^^^^^^^

.. java:method:: @ExceptionHandler @ResponseStatus @ResponseBody public String handleMdsException(MdsException exception) throws IOException
   :outertype: MdsController

setExampleData
^^^^^^^^^^^^^^

.. java:method:: static void setExampleData(ExampleData exampleData)
   :outertype: MdsController

