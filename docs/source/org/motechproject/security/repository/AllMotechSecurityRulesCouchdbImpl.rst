.. java:import:: java.util ArrayList

.. java:import:: java.util Collections

.. java:import:: java.util List

.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.ektorp CouchDbConnector

.. java:import:: org.ektorp ViewQuery

.. java:import:: org.ektorp.support View

.. java:import:: org.motechproject.commons.couchdb.dao MotechBaseRepository

.. java:import:: org.motechproject.security.domain MotechSecurityConfiguration

.. java:import:: org.motechproject.security.domain MotechURLSecurityRule

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.stereotype Component

AllMotechSecurityRulesCouchdbImpl
=================================

.. java:package:: org.motechproject.security.repository
   :noindex:

.. java:type:: @Component @View public class AllMotechSecurityRulesCouchdbImpl extends MotechBaseRepository<MotechSecurityConfiguration> implements AllMotechSecurityRules

   Implementation of DAO interface that utilizes a CouchDB back-end for storage. Only one MotechSecurityConfiguration file should be saved at a time, so adding the document looks for the old document in order to update it if it already exists. Rather than updating the object reference, the old configuration's ID and revision are used for the new document.

Constructors
------------
AllMotechSecurityRulesCouchdbImpl
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: @Autowired protected AllMotechSecurityRulesCouchdbImpl(CouchDbConnector db)
   :outertype: AllMotechSecurityRulesCouchdbImpl

Methods
-------
addOrUpdate
^^^^^^^^^^^

.. java:method:: @Override public void addOrUpdate(MotechSecurityConfiguration config)
   :outertype: AllMotechSecurityRulesCouchdbImpl

getMotechSecurityConfiguration
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Override public MotechSecurityConfiguration getMotechSecurityConfiguration()
   :outertype: AllMotechSecurityRulesCouchdbImpl

getRules
^^^^^^^^

.. java:method:: @Override public List<MotechURLSecurityRule> getRules()
   :outertype: AllMotechSecurityRulesCouchdbImpl

getRulesByOrigin
^^^^^^^^^^^^^^^^

.. java:method:: @Override @View public List<MotechURLSecurityRule> getRulesByOrigin(String origin)
   :outertype: AllMotechSecurityRulesCouchdbImpl

