EntityReadOnlyException
=======================

.. java:package:: org.motechproject.mds.ex
   :noindex:

.. java:type:: public class EntityReadOnlyException extends MdsException

   The \ ``EntityReadOnlyException``\  exception signals a situation in which a user wants to make changes on an entity which is read only (it was created by a module).

Constructors
------------
EntityReadOnlyException
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public EntityReadOnlyException()
   :outertype: EntityReadOnlyException

   Constructs a new EntityReadOnlyException with \ *mds.error.entityIsReadOnly*\  as a message key.

