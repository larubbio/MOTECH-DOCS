.. java:import:: org.apache.commons.lang StringUtils

SelectData
==========

.. java:package:: org.motechproject.mds.web
   :noindex:

.. java:type:: public class SelectData

   The \ ``SelectData``\  class contains information from select2.js ajax request.

   The class contains information such as:

   ..

   * \ **term**\  - it can consist of several strings connected with a \ **,**\  character. Only three first strings are taken into consideration, others are ignored. By default it is equal to \ :java:ref:`DEFAULT_TERM`\ .
   * \ **pageLimit**\  - number of records which should be on one page. By default it is equal to \ :java:ref:`DEFAULT_PAGE_LIMIT`\ .
   * \ **page**\  - number of the page which should be returned. By default it is equal to \ :java:ref:`DEFAULT_PAGE`\ .

Fields
------
DEFAULT_PAGE
^^^^^^^^^^^^

.. java:field:: public static final Integer DEFAULT_PAGE
   :outertype: SelectData

   The constant \ ``DEFAULT_PAGE``\  presents the default page number.

DEFAULT_PAGE_LIMIT
^^^^^^^^^^^^^^^^^^

.. java:field:: public static final Integer DEFAULT_PAGE_LIMIT
   :outertype: SelectData

   The constant \ ``DEFAULT_PAGE_LIMIT``\  presents the default number of records on one page.

DEFAULT_TERM
^^^^^^^^^^^^

.. java:field:: public static final String DEFAULT_TERM
   :outertype: SelectData

   The constant \ ``DEFAULT_TERM``\  presents the default term used to find specific entity.

Constructors
------------
SelectData
^^^^^^^^^^

.. java:constructor:: public SelectData()
   :outertype: SelectData

SelectData
^^^^^^^^^^

.. java:constructor:: public SelectData(String term, Integer page, Integer pageLimit)
   :outertype: SelectData

Methods
-------
getPage
^^^^^^^

.. java:method:: public Integer getPage()
   :outertype: SelectData

getPageLimit
^^^^^^^^^^^^

.. java:method:: public Integer getPageLimit()
   :outertype: SelectData

getTerm
^^^^^^^

.. java:method:: public String getTerm()
   :outertype: SelectData

setPage
^^^^^^^

.. java:method:: public void setPage(Integer page)
   :outertype: SelectData

setPageLimit
^^^^^^^^^^^^

.. java:method:: public void setPageLimit(Integer pageLimit)
   :outertype: SelectData

setTerm
^^^^^^^

.. java:method:: public void setTerm(String term)
   :outertype: SelectData

