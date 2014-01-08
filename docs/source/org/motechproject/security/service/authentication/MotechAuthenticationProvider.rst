.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.motechproject.security.authentication MotechPasswordEncoder

.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.domain MotechUserProfile

.. java:import:: org.motechproject.security.repository AllMotechUsers

.. java:import:: org.motechproject.security.service AuthoritiesService

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.authentication BadCredentialsException

.. java:import:: org.springframework.security.authentication UsernamePasswordAuthenticationToken

.. java:import:: org.springframework.security.authentication.dao AbstractUserDetailsAuthenticationProvider

.. java:import:: org.springframework.security.core.userdetails User

.. java:import:: org.springframework.security.core.userdetails UserDetails

.. java:import:: org.springframework.stereotype Component

MotechAuthenticationProvider
============================

.. java:package:: org.motechproject.security.service.authentication
   :noindex:

.. java:type:: @Component public class MotechAuthenticationProvider extends AbstractUserDetailsAuthenticationProvider

   Extends Spring's @AbstractUserDetailsAuthenticationProvider to provide implementation for the API retrieve user and additional checks on password.

Fields
------
PLEASE_ENTER_PASSWORD
^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String PLEASE_ENTER_PASSWORD
   :outertype: MotechAuthenticationProvider

USER_NOT_ACTIVATED
^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String USER_NOT_ACTIVATED
   :outertype: MotechAuthenticationProvider

USER_NOT_FOUND
^^^^^^^^^^^^^^

.. java:field:: public static final String USER_NOT_FOUND
   :outertype: MotechAuthenticationProvider

Constructors
------------
MotechAuthenticationProvider
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired public MotechAuthenticationProvider(AllMotechUsers allMotechUsers, MotechPasswordEncoder motechPasswordEncoder, AuthoritiesService authoritiesService)
   :outertype: MotechAuthenticationProvider

Methods
-------
additionalAuthenticationChecks
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override protected void additionalAuthenticationChecks(UserDetails userDetails, UsernamePasswordAuthenticationToken authentication)
   :outertype: MotechAuthenticationProvider

retrieveUser
^^^^^^^^^^^^

.. java:method:: @Override protected UserDetails retrieveUser(String username, UsernamePasswordAuthenticationToken authentication)
   :outertype: MotechAuthenticationProvider

