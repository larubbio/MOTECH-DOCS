.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: java.util ArrayList

.. java:import:: java.util Arrays

.. java:import:: java.util List

.. java:import:: java.util Objects

.. java:import:: java.util.regex Matcher

.. java:import:: java.util.regex Pattern

KeyInformation
==============

.. java:package:: org.motechproject.tasks.domain
   :noindex:

.. java:type:: public final class KeyInformation

   Object representation of dragged field from trigger or data source.

   This class represents a single dragged field from trigger or data source. This class does not expose a public constructor. You have to use \ :java:ref:`parse(String)`\  method if you want to parse single field or \ :java:ref:`parseAll(String)`\  if you want ot get all fields from a given string.

Fields
------
ADDITIONAL_DATA_PREFIX
^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String ADDITIONAL_DATA_PREFIX
   :outertype: KeyInformation

   Prefix which is used for data source fields.

TRIGGER_PREFIX
^^^^^^^^^^^^^^

.. java:field:: public static final String TRIGGER_PREFIX
   :outertype: KeyInformation

   Prefix which is used for trigger fields.

Methods
-------
equals
^^^^^^

.. java:method:: @Override public boolean equals(Object obj)
   :outertype: KeyInformation

fromAdditionalData
^^^^^^^^^^^^^^^^^^

.. java:method:: public boolean fromAdditionalData()
   :outertype: KeyInformation

   Check if the field is from the data source.

   :return: true if the field is from the data source otherwise false

fromTrigger
^^^^^^^^^^^

.. java:method:: public boolean fromTrigger()
   :outertype: KeyInformation

   Check if the field is from the trigger.

   :return: true if the field is from the trigger otherwise false

getDataProviderId
^^^^^^^^^^^^^^^^^

.. java:method:: public String getDataProviderId()
   :outertype: KeyInformation

getKey
^^^^^^

.. java:method:: public String getKey()
   :outertype: KeyInformation

getManipulations
^^^^^^^^^^^^^^^^

.. java:method:: public List<String> getManipulations()
   :outertype: KeyInformation

   Get manipulations assigned to the field.

   :return: list of manipulations

getObjectId
^^^^^^^^^^^

.. java:method:: public Long getObjectId()
   :outertype: KeyInformation

getObjectType
^^^^^^^^^^^^^

.. java:method:: public String getObjectType()
   :outertype: KeyInformation

getOriginalKey
^^^^^^^^^^^^^^

.. java:method:: public String getOriginalKey()
   :outertype: KeyInformation

   Get original representation of the dragged field.

   :return: string representation of the field

getPrefix
^^^^^^^^^

.. java:method:: public String getPrefix()
   :outertype: KeyInformation

hasManipulations
^^^^^^^^^^^^^^^^

.. java:method:: public boolean hasManipulations()
   :outertype: KeyInformation

   Check if the field has any manipulations.

   :return: true if the field has manipulations otherwise false

hashCode
^^^^^^^^

.. java:method:: @Override public int hashCode()
   :outertype: KeyInformation

parse
^^^^^

.. java:method:: public static KeyInformation parse(String input)
   :outertype: KeyInformation

   Parse given string to instance of \ :java:ref:`KeyInformation`\ .

   This method should be used to convert string representation of dragged field to instance of \ :java:ref:`KeyInformation`\ .

   Argument has adhere to one of the following format:

   ..

   * trigger field format: \ **trigger.eventKey**\
   * data source format: \ **ad.dataProviderId.objectType#objectId.fieldKey**\

   Argument can also contain list of manipulation which should be executed on field before it will be used by \ :java:ref:`org.motechproject.tasks.service.TaskTriggerHandler`\  class. Manipulations should be connected together by the \ **?**\  character.

   Example of input argument:

   ..

   * ad.279f5fdf60700d9717270b1ae3011eb1.CaseInfo#0.fieldValues.phu_id
   * trigger.message?format(Ala,cat)?capitalize

   :param input: string representation of a dragged field from trigger or data source
   :return: Object representation of a dragged field

parseAll
^^^^^^^^

.. java:method:: public static List<KeyInformation> parseAll(String input)
   :outertype: KeyInformation

   Find all fields from given input and convert them to the instance of \ :java:ref:`KeyInformation`\ .

   This method should be used to find and convert all of string representation of the field from trigger and/or data sources. Fields in input have to adhere to one of the following formats:

   ..

   * trigger field format: \ **{{trigger.eventKey}}**\
   * data source format: \ **{{ad.dataProviderId.objectType#objectId.fieldKey}}**\

   To find fields in the input argument this method uses regular expression. When field is found it is converted to an instance of \ :java:ref:`KeyInformation`\  by using the \ :java:ref:`parse(String)`\  method.

   Fields are found by the following regular expression: \ **\{\{((.*?))(\}\})(?![^(]*\))**\ . The expression searches for strings that start with \ *{{*\  and end with \ *}}*\  and are not within \ *(*\  and \ *)*\ . Because of manipulations which contain additional data in \ *(...)*\  needed to execute manipulation on the field (e.g.: join needs to have the join character) and the text in \ *(...)*\  can be another string representation of the dragged field, the expression has to check if the field has this kind of manipulation.

   Example of input argument:

   ..

   * {{trigger.message?format(Ala,cat)?capitalize}}
   * You get the following message: {{trigger.message}}

   :param input: string with one or more string representation of dragged fields from trigger and/or data sources
   :return: list of object representation of dragged fields.

