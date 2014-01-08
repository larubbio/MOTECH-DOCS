.. java:import:: org.hamcrest BaseMatcher

.. java:import:: org.hamcrest Description

.. java:import:: java.io File

.. java:import:: java.util List

FileListMatcher
===============

.. java:package:: org.motechproject.config.core.domain
   :noindex:

.. java:type:: public class FileListMatcher extends BaseMatcher<List<File>>

Methods
-------
describeTo
^^^^^^^^^^

.. java:method:: @Override public void describeTo(Description description)
   :outertype: FileListMatcher

doesNotHave
^^^^^^^^^^^

.. java:method:: public static FileListMatcher doesNotHave(String fileName)
   :outertype: FileListMatcher

has
^^^

.. java:method:: public static FileListMatcher has(String fileName)
   :outertype: FileListMatcher

matches
^^^^^^^

.. java:method:: @Override public boolean matches(Object item)
   :outertype: FileListMatcher

