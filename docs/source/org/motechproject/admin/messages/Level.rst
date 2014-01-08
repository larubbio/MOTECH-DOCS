.. java:import:: org.codehaus.jackson.annotate JsonValue

Level
=====

.. java:package:: org.motechproject.admin.messages
   :noindex:

.. java:type:: public enum Level

   Represents the level of a \ :java:ref:`org.motechproject.admin.domain.StatusMessage`\ , which is reflected on the UI. Posting a \ :java:ref:`org.motechproject.admin.domain.StatusMessage`\  with a \ ``CRITICAL``\  level will trigger notifications.

Enum Constants
--------------
CRITICAL
^^^^^^^^

.. java:field:: public static final Level CRITICAL
   :outertype: Level

DEBUG
^^^^^

.. java:field:: public static final Level DEBUG
   :outertype: Level

ERROR
^^^^^

.. java:field:: public static final Level ERROR
   :outertype: Level

INFO
^^^^

.. java:field:: public static final Level INFO
   :outertype: Level

WARN
^^^^

.. java:field:: public static final Level WARN
   :outertype: Level

