.. java:import:: java.util Collection

.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.motechproject.security.constants SecurityConfigConstants

.. java:import:: org.motechproject.security.domain MotechUserProfile

.. java:import:: org.springframework.security.access AccessDecisionVoter

.. java:import:: org.springframework.security.access ConfigAttribute

.. java:import:: org.springframework.security.core Authentication

MotechAccessVoter
=================

.. java:package:: org.motechproject.security.authentication
   :noindex:

.. java:type:: public class MotechAccessVoter implements AccessDecisionVoter<Object>

   A custom AccessDecisionVoter for voting on whether a specific user has access to a particular URL. For example, a security rule can specify that the users motech and admin have access to a particular URL. This loads the metadata source with attributes for ACCESS_motech and ACCESS_admin. When a user invokes that URL, an affirmative based voting system will check whether or not the user is motech or admin. If not, they are denied permission, otherwise they are granted access.

Methods
-------
supports
^^^^^^^^

.. java:method:: @Override public boolean supports(ConfigAttribute attribute)
   :outertype: MotechAccessVoter

supports
^^^^^^^^

.. java:method:: @Override public boolean supports(Class<?> clazz)
   :outertype: MotechAccessVoter

vote
^^^^

.. java:method:: @Override public int vote(Authentication authentication, Object object, Collection<ConfigAttribute> attributes)
   :outertype: MotechAccessVoter

