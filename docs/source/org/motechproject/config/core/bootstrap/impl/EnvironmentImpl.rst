.. java:import:: org.motechproject.config.core.bootstrap Environment

.. java:import:: org.springframework.stereotype Component

EnvironmentImpl
===============

.. java:package:: org.motechproject.config.core.bootstrap.impl
   :noindex:

.. java:type:: @Component public class EnvironmentImpl implements Environment

Methods
-------
getConfigDir
^^^^^^^^^^^^

.. java:method:: @Override public String getConfigDir()
   :outertype: EnvironmentImpl

getConfigSource
^^^^^^^^^^^^^^^

.. java:method:: @Override public String getConfigSource()
   :outertype: EnvironmentImpl

getDBPassword
^^^^^^^^^^^^^

.. java:method:: @Override public String getDBPassword()
   :outertype: EnvironmentImpl

getDBUrl
^^^^^^^^

.. java:method:: @Override public String getDBUrl()
   :outertype: EnvironmentImpl

getDBUsername
^^^^^^^^^^^^^

.. java:method:: @Override public String getDBUsername()
   :outertype: EnvironmentImpl

getTenantId
^^^^^^^^^^^

.. java:method:: @Override public String getTenantId()
   :outertype: EnvironmentImpl

getValue
^^^^^^^^

.. java:method::  String getValue(String variableName)
   :outertype: EnvironmentImpl

