.. java:import:: java.util List

SelectResult
============

.. java:package:: org.motechproject.mds.web
   :noindex:

.. java:type:: public class SelectResult<T>

   The \ ``SelectResult``\  class contains information which will be returned to select2.js.

   The class contains information such as:

   ..

   * \ **results**\  - this is a list consisting of up to \ :java:ref:`org.motechproject.mds.web.SelectData.getPageLimit()`\  records, which are of the \ :java:ref:`org.motechproject.mds.dto.EntityDto`\  type,
   * \ **more**\  - it equals to \ *true*\  if select2.js should load more data if user reaches the end of the list; otherwise it equals to \ *false*\ .

Constructors
------------
SelectResult
^^^^^^^^^^^^

.. java:constructor:: public SelectResult(SelectData data, List<T> list)
   :outertype: SelectResult

Methods
-------
getResults
^^^^^^^^^^

.. java:method:: public List<T> getResults()
   :outertype: SelectResult

isMore
^^^^^^

.. java:method:: public boolean isMore()
   :outertype: SelectResult

