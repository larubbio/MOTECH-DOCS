.. java:import:: org.springframework.security.core GrantedAuthority

.. java:import:: org.springframework.security.core.authority SimpleGrantedAuthority

.. java:import:: org.springframework.security.core.userdetails User

.. java:import:: org.springframework.security.core.userdetails UserDetails

.. java:import:: org.springframework.security.core.userdetails UserDetailsService

.. java:import:: org.springframework.security.core.userdetails UsernameNotFoundException

.. java:import:: java.util ArrayList

.. java:import:: java.util List

StubUserService
===============

.. java:package:: org.motechproject.security
   :noindex:

.. java:type:: public class StubUserService implements UserDetailsService

Fields
------
USER_WITHOUT_PERMISSION_TO_MANAGE_ROLES
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String USER_WITHOUT_PERMISSION_TO_MANAGE_ROLES
   :outertype: StubUserService

USER_WITH_PERMISSION_TO_MANAGE_ROLES
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String USER_WITH_PERMISSION_TO_MANAGE_ROLES
   :outertype: StubUserService

Methods
-------
loadUserByUsername
^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public UserDetails loadUserByUsername(String username) throws UsernameNotFoundException
   :outertype: StubUserService

