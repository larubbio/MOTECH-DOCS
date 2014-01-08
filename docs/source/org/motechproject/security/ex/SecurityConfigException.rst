SecurityConfigException
=======================

.. java:package:: org.motechproject.security.ex
   :noindex:

.. java:type:: public class SecurityConfigException extends RuntimeException

   A runtime exception thrown when the security config does not pass validation constraints required in order to construct a new security chain. Ideally should not be thrown as the UI should not allow invalid data to be submitted.

Constructors
------------
SecurityConfigException
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public SecurityConfigException(String message)
   :outertype: SecurityConfigException

