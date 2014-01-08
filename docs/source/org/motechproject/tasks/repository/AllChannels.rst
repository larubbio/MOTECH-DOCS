.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp.support View

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.tasks.domain Channel

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Repository

.. java:import:: java.util List

AllChannels
===========

.. java:package:: org.motechproject.tasks.repository
   :noindex:

.. java:type:: @Repository @View public class AllChannels extends MotechBaseRepository<Channel>

Constructors
------------
AllChannels
^^^^^^^^^^^

.. java:constructor:: @Autowired public AllChannels(CouchDbConnector connector)
   :outertype: AllChannels

Methods
-------
addOrUpdate
^^^^^^^^^^^

.. java:method:: public boolean addOrUpdate(Channel channel)
   :outertype: AllChannels

byModuleName
^^^^^^^^^^^^

.. java:method:: public Channel byModuleName(String moduleName)
   :outertype: AllChannels

