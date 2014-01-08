.. java:import:: org.motechproject.security.domain MotechRole

.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.repository AllMotechRoles

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.security.core GrantedAuthority

.. java:import:: org.springframework.security.core.authority SimpleGrantedAuthority

.. java:import:: org.springframework.stereotype Service

.. java:import:: java.util ArrayList

.. java:import:: java.util List

AuthoritiesServiceImpl
======================

.. java:package:: org.motechproject.security.service
   :noindex:

.. java:type:: @Service public class AuthoritiesServiceImpl implements AuthoritiesService

   Implementation for @AuthoritiesService.Given a MotechUser, retrieves the roles granted to that user and for each role collects permissions associated with the role.

Methods
-------
authoritiesFor
^^^^^^^^^^^^^^

.. java:method:: @Override public List<GrantedAuthority> authoritiesFor(MotechUser user)
   :outertype: AuthoritiesServiceImpl

