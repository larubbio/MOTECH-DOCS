.. java:import:: org.apache.commons.lang StringUtils

Tenant
======

.. java:package:: org.motechproject.commons.api
   :noindex:

.. java:type:: public class Tenant

Constructors
------------
Tenant
^^^^^^

.. java:constructor::  Tenant(TenantIdentity identity)
   :outertype: Tenant

Methods
-------
canHaveQueue
^^^^^^^^^^^^

.. java:method:: public boolean canHaveQueue(String queueName)
   :outertype: Tenant

current
^^^^^^^

.. java:method:: public static Tenant current()
   :outertype: Tenant

getId
^^^^^

.. java:method:: public String getId()
   :outertype: Tenant

getSuffixedId
^^^^^^^^^^^^^

.. java:method:: public String getSuffixedId()
   :outertype: Tenant

