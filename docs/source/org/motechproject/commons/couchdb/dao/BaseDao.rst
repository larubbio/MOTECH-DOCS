.. java:import:: org.motechproject.commons.couchdb.model MotechBaseDataObject

.. java:import:: java.util List

BaseDao
=======

.. java:package:: org.motechproject.commons.couchdb.dao
   :noindex:

.. java:type:: public interface BaseDao<T extends MotechBaseDataObject>

Methods
-------
add
^^^

.. java:method::  void add(T entity)
   :outertype: BaseDao

contains
^^^^^^^^

.. java:method::  boolean contains(String id)
   :outertype: BaseDao

get
^^^

.. java:method::  T get(String id)
   :outertype: BaseDao

getAll
^^^^^^

.. java:method::  List<T> getAll()
   :outertype: BaseDao

remove
^^^^^^

.. java:method::  void remove(T entity)
   :outertype: BaseDao

safeRemove
^^^^^^^^^^

.. java:method::  void safeRemove(T entity)
   :outertype: BaseDao

update
^^^^^^

.. java:method::  void update(T entity)
   :outertype: BaseDao

