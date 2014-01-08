MdsException
============

.. java:package:: org.motechproject.mds.ex
   :noindex:

.. java:type:: public class MdsException extends RuntimeException

   The \ ``MdsException``\  exception is a basic class for all other exceptions defined in the mds module. It contains information about a message key which will be used on UI to present a message in appropriate language.

Constructors
------------
MdsException
^^^^^^^^^^^^

.. java:constructor:: public MdsException(String messageKey)
   :outertype: MdsException

   Constructs a new mds exception with the specified message key.

   :param messageKey: the message key used later to display message in appropriate language on UI.

Methods
-------
getMessageKey
^^^^^^^^^^^^^

.. java:method:: public String getMessageKey()
   :outertype: MdsException

