.. java:import:: java.util ArrayList

.. java:import:: java.util HashSet

.. java:import:: java.util List

.. java:import:: java.util Set

.. java:import:: org.motechproject.security.constants SecurityConfigConstants

.. java:import:: org.motechproject.security.domain MotechSecurityConfiguration

.. java:import:: org.motechproject.security.domain MotechURLSecurityRule

SecurityTestConfigBuilder
=========================

.. java:package:: org.motechproject.security.osgi.helper
   :noindex:

.. java:type:: public final class SecurityTestConfigBuilder

   A builder class for building security rules programatically in order for manual testing. Typically rules should only be created from JSON from modules or the UI.

Fields
------
LOGIN_ACCESS_TEST
^^^^^^^^^^^^^^^^^

.. java:field:: public static final String LOGIN_ACCESS_TEST
   :outertype: SecurityTestConfigBuilder

METHOD_SPECIFIC_TEST
^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String METHOD_SPECIFIC_TEST
   :outertype: SecurityTestConfigBuilder

NO_SECURITY_TEST
^^^^^^^^^^^^^^^^

.. java:field:: public static final String NO_SECURITY_TEST
   :outertype: SecurityTestConfigBuilder

PERMISSION_ACCESS_TEST
^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String PERMISSION_ACCESS_TEST
   :outertype: SecurityTestConfigBuilder

USER_ACCESS_TEST
^^^^^^^^^^^^^^^^

.. java:field:: public static final String USER_ACCESS_TEST
   :outertype: SecurityTestConfigBuilder

Methods
-------
buildConfig
^^^^^^^^^^^

.. java:method:: public static MotechSecurityConfiguration buildConfig(String testOption, String configOption, String configOption2)
   :outertype: SecurityTestConfigBuilder

