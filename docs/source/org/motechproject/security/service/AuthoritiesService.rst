.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.springframework.security.core GrantedAuthority

.. java:import:: java.util List

AuthoritiesService
==================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: public interface AuthoritiesService

   Service interface to retrieve authorities(permissions) for a given MotechUser

Methods
-------
authoritiesFor
^^^^^^^^^^^^^^

.. java:method::  List<GrantedAuthority> authoritiesFor(MotechUser user)
   :outertype: AuthoritiesService

