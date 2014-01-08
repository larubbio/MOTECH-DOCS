.. java:import:: org.motechproject.security.domain MotechRole

.. java:import:: java.util List

AllMotechRoles
==============

.. java:package:: org.motechproject.security.repository
   :noindex:

.. java:type:: public interface AllMotechRoles

Methods
-------
add
^^^

.. java:method::  void add(MotechRole role)
   :outertype: AllMotechRoles

findByRoleName
^^^^^^^^^^^^^^

.. java:method::  MotechRole findByRoleName(String roleName)
   :outertype: AllMotechRoles

getRoles
^^^^^^^^

.. java:method::  List<MotechRole> getRoles()
   :outertype: AllMotechRoles

remove
^^^^^^

.. java:method::  void remove(MotechRole motechRole)
   :outertype: AllMotechRoles

update
^^^^^^

.. java:method::  void update(MotechRole motechRole)
   :outertype: AllMotechRoles

