.. java:import:: java.io Serializable

ModuleMenuLink
==============

.. java:package:: org.motechproject.server.web.dto
   :noindex:

.. java:type:: public class ModuleMenuLink implements Serializable

   A class representing a link displayed in the left hand nav menu.

Constructors
------------
ModuleMenuLink
^^^^^^^^^^^^^^

.. java:constructor:: public ModuleMenuLink(String name, String moduleName, String url, boolean needsAttention)
   :outertype: ModuleMenuLink

Methods
-------
getModuleName
^^^^^^^^^^^^^

.. java:method:: public String getModuleName()
   :outertype: ModuleMenuLink

   Name of the module to which this link belongs to. Required for building the url.

   :return: the module to which this link belongs to.

getName
^^^^^^^

.. java:method:: public String getName()
   :outertype: ModuleMenuLink

   Text that is displayed as this link.

   :return: link text content.

getUrl
^^^^^^

.. java:method:: public String getUrl()
   :outertype: ModuleMenuLink

   Url that is appended at the end of this links. In most cases an anchor to the partial loaded by AngularJS.

   :return: url to be appended.

hasUrl
^^^^^^

.. java:method:: public boolean hasUrl(String linkUrl)
   :outertype: ModuleMenuLink

isNeedsAttention
^^^^^^^^^^^^^^^^

.. java:method:: public boolean isNeedsAttention()
   :outertype: ModuleMenuLink

   Specifies whether this link should be marked on the UI with a warning sign.

   :return: true if this module needs attention, false otherwise.

setModuleName
^^^^^^^^^^^^^

.. java:method:: public void setModuleName(String moduleName)
   :outertype: ModuleMenuLink

setName
^^^^^^^

.. java:method:: public void setName(String name)
   :outertype: ModuleMenuLink

setNeedsAttention
^^^^^^^^^^^^^^^^^

.. java:method:: public void setNeedsAttention(boolean needsAttention)
   :outertype: ModuleMenuLink

setUrl
^^^^^^

.. java:method:: public void setUrl(String url)
   :outertype: ModuleMenuLink

