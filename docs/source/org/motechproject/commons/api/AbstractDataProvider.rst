.. java:import:: org.apache.commons.io IOUtils

.. java:import:: org.springframework.core.io Resource

.. java:import:: java.io IOException

.. java:import:: java.io InputStream

.. java:import:: java.io StringWriter

.. java:import:: java.util List

AbstractDataProvider
====================

.. java:package:: org.motechproject.commons.api
   :noindex:

.. java:type:: public abstract class AbstractDataProvider extends MotechObject implements DataProvider

Methods
-------
getBody
^^^^^^^

.. java:method:: protected String getBody()
   :outertype: AbstractDataProvider

getClassForType
^^^^^^^^^^^^^^^

.. java:method:: protected Class<?> getClassForType(String type) throws ClassNotFoundException
   :outertype: AbstractDataProvider

getPackageRoot
^^^^^^^^^^^^^^

.. java:method:: public abstract String getPackageRoot()
   :outertype: AbstractDataProvider

getSupportClasses
^^^^^^^^^^^^^^^^^

.. java:method:: public abstract List<Class<?>> getSupportClasses()
   :outertype: AbstractDataProvider

isAssignable
^^^^^^^^^^^^

.. java:method:: protected boolean isAssignable(Class<?> check, List<Class<?>> classes)
   :outertype: AbstractDataProvider

setBody
^^^^^^^

.. java:method:: protected void setBody(Resource resource)
   :outertype: AbstractDataProvider

supports
^^^^^^^^

.. java:method:: @Override public boolean supports(String type)
   :outertype: AbstractDataProvider

toJSON
^^^^^^

.. java:method:: @Override public String toJSON()
   :outertype: AbstractDataProvider

