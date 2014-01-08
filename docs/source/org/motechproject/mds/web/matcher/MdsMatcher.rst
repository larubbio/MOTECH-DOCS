.. java:import:: org.apache.commons.collections Predicate

.. java:import:: java.util ArrayList

.. java:import:: java.util List

MdsMatcher
==========

.. java:package:: org.motechproject.mds.web.matcher
   :noindex:

.. java:type:: public abstract class MdsMatcher<T> implements Predicate

   The \ ``MdsMatcher``\  is a basic generic wrapper for all matchers inside mds module.

Constructors
------------
MdsMatcher
^^^^^^^^^^

.. java:constructor:: protected MdsMatcher(Class<T> clazz)
   :outertype: MdsMatcher

MdsMatcher
^^^^^^^^^^

.. java:constructor:: protected MdsMatcher(Class<T> clazz, String term)
   :outertype: MdsMatcher

Methods
-------
evaluate
^^^^^^^^

.. java:method:: @Override public boolean evaluate(Object object)
   :outertype: MdsMatcher

   {@inheritDoc}

getFirstTerm
^^^^^^^^^^^^

.. java:method:: protected String getFirstTerm()
   :outertype: MdsMatcher

getFirstTerm
^^^^^^^^^^^^

.. java:method:: protected String getFirstTerm(String splitChar)
   :outertype: MdsMatcher

getTerm
^^^^^^^

.. java:method:: protected String getTerm()
   :outertype: MdsMatcher

getTerms
^^^^^^^^

.. java:method:: protected List<String> getTerms(int numberOfTerms)
   :outertype: MdsMatcher

getTerms
^^^^^^^^

.. java:method:: protected List<String> getTerms(int numberOfTerms, String splitChar)
   :outertype: MdsMatcher

match
^^^^^

.. java:method:: protected abstract boolean match(T obj)
   :outertype: MdsMatcher

