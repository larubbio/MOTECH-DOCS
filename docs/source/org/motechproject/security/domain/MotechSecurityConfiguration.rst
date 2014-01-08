.. java:import:: java.util List

.. java:import:: org.codehaus.jackson.annotate JsonProperty

.. java:import:: org.ektorp.support TypeDiscriminator

.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

MotechSecurityConfiguration
===========================

.. java:package:: org.motechproject.security.domain
   :noindex:

.. java:type:: @TypeDiscriminator public class MotechSecurityConfiguration extends MotechBaseDataObject

   The MotechSecurityConfiguration is a single document that contains all of the URL security rule configuration. The configuration was designed as one document because the entire filter chain must be reconstructed each time it is updated, therefore managing many references is unnecessary.

Fields
------
DOC_TYPE
^^^^^^^^

.. java:field:: public static final String DOC_TYPE
   :outertype: MotechSecurityConfiguration

Constructors
------------
MotechSecurityConfiguration
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechSecurityConfiguration()
   :outertype: MotechSecurityConfiguration

MotechSecurityConfiguration
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public MotechSecurityConfiguration(List<MotechURLSecurityRule> securityRules)
   :outertype: MotechSecurityConfiguration

Methods
-------
getSecurityRules
^^^^^^^^^^^^^^^^

.. java:method:: public List<MotechURLSecurityRule> getSecurityRules()
   :outertype: MotechSecurityConfiguration

setSecurityRules
^^^^^^^^^^^^^^^^

.. java:method:: public void setSecurityRules(List<MotechURLSecurityRule> securityRules)
   :outertype: MotechSecurityConfiguration

