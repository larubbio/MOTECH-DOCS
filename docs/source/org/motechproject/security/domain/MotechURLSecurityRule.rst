.. java:import:: java.io Serializable

.. java:import:: java.util List

.. java:import:: java.util Set

MotechURLSecurityRule
=====================

.. java:package:: org.motechproject.security.domain
   :noindex:

.. java:type:: public class MotechURLSecurityRule implements Serializable

   The MotechURLSecurityRule specifies the configuration for setting up a Spring SecurityFilterChain. See the SecurityConfigConstants class for valid values for supportedSchemes, protocol and methodsRequired Details regarding configuration: pattern: URL pattern the security rule applies to supportedSchemes: Security rules that should apply to the URL, such as BASIC or OPEN_ID protocol: Protocol the security rule applies to, such as HTTP or HTTPS permissionAccess: Requires user has at least one of the listed permission to access the URL userAccess: User specific access for a URL, such as motech or admin, when combined with permission access they act as an either or (one must be true) priority: For future use in determining the ordering of filter chains, may be deprecated depending on UI implementation rest: Whether the endpoint is meant for a form login process or as an REST end-point that does not create a session for the origin: The module or user the rule originated from version: The version of the module or platform the rule was created methodsRequired: HTTP methods the rule applies to, if ANY is used then any method is matched, if a set is used, such as GET, POST, etc, then each will have its own corresponding filter chain with the same security found in that rule

Methods
-------
getActive
^^^^^^^^^

.. java:method:: public boolean getActive()
   :outertype: MotechURLSecurityRule

getMethodsRequired
^^^^^^^^^^^^^^^^^^

.. java:method:: public Set<String> getMethodsRequired()
   :outertype: MotechURLSecurityRule

getOrigin
^^^^^^^^^

.. java:method:: public String getOrigin()
   :outertype: MotechURLSecurityRule

getPattern
^^^^^^^^^^

.. java:method:: public String getPattern()
   :outertype: MotechURLSecurityRule

getPermissionAccess
^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<String> getPermissionAccess()
   :outertype: MotechURLSecurityRule

getPriority
^^^^^^^^^^^

.. java:method:: public int getPriority()
   :outertype: MotechURLSecurityRule

getProtocol
^^^^^^^^^^^

.. java:method:: public String getProtocol()
   :outertype: MotechURLSecurityRule

getSupportedSchemes
^^^^^^^^^^^^^^^^^^^

.. java:method:: public List<String> getSupportedSchemes()
   :outertype: MotechURLSecurityRule

getUserAccess
^^^^^^^^^^^^^

.. java:method:: public List<String> getUserAccess()
   :outertype: MotechURLSecurityRule

getVersion
^^^^^^^^^^

.. java:method:: public String getVersion()
   :outertype: MotechURLSecurityRule

isRest
^^^^^^

.. java:method:: public boolean isRest()
   :outertype: MotechURLSecurityRule

setActive
^^^^^^^^^

.. java:method:: public void setActive(boolean active)
   :outertype: MotechURLSecurityRule

setMethodsRequired
^^^^^^^^^^^^^^^^^^

.. java:method:: public void setMethodsRequired(Set<String> methodsRequired)
   :outertype: MotechURLSecurityRule

setOrigin
^^^^^^^^^

.. java:method:: public void setOrigin(String origin)
   :outertype: MotechURLSecurityRule

setPattern
^^^^^^^^^^

.. java:method:: public void setPattern(String pattern)
   :outertype: MotechURLSecurityRule

setPermissionAccess
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setPermissionAccess(List<String> permissionAccess)
   :outertype: MotechURLSecurityRule

setPriority
^^^^^^^^^^^

.. java:method:: public void setPriority(int priority)
   :outertype: MotechURLSecurityRule

setProtocol
^^^^^^^^^^^

.. java:method:: public void setProtocol(String protocol)
   :outertype: MotechURLSecurityRule

setRest
^^^^^^^

.. java:method:: public void setRest(boolean rest)
   :outertype: MotechURLSecurityRule

setSupportedSchemes
^^^^^^^^^^^^^^^^^^^

.. java:method:: public void setSupportedSchemes(List<String> supportedSchemes)
   :outertype: MotechURLSecurityRule

setUserAccess
^^^^^^^^^^^^^

.. java:method:: public void setUserAccess(List<String> userAccess)
   :outertype: MotechURLSecurityRule

setVersion
^^^^^^^^^^

.. java:method:: public void setVersion(String version)
   :outertype: MotechURLSecurityRule

