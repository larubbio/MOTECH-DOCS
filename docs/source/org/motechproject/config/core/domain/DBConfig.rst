.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.motechproject.config.core MotechConfigurationException

.. java:import:: java.net MalformedURLException

.. java:import:: java.net URISyntaxException

.. java:import:: java.net URL

DBConfig
========

.. java:package:: org.motechproject.config.core.domain
   :noindex:

.. java:type:: public class DBConfig

   DBConfig encapsulates the database configuration, composed of as db url, username and password.

Constructors
------------
DBConfig
^^^^^^^^

.. java:constructor:: public DBConfig(String url, String username, String password)
   :outertype: DBConfig

   :param url:
   :param username:
   :param password:

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object o)
   :outertype: DBConfig

getPassword
^^^^^^^^^^^

.. java:method:: public String getPassword()
   :outertype: DBConfig

getUrl
^^^^^^

.. java:method:: public String getUrl()
   :outertype: DBConfig

getUsername
^^^^^^^^^^^

.. java:method:: public String getUsername()
   :outertype: DBConfig

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: DBConfig

toString
^^^^^^^^

.. java:method:: @Override public String toString()
   :outertype: DBConfig

