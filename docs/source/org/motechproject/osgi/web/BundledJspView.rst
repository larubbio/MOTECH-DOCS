.. java:import:: org.eclipse.gemini.blueprint.context BundleContextAware

.. java:import:: org.motechproject.osgi.web.exception RenderException

.. java:import:: org.osgi.framework BundleContext

.. java:import:: org.springframework.web.servlet.view JstlView

.. java:import:: javax.servlet.http HttpServletRequest

.. java:import:: javax.servlet.http HttpServletResponse

.. java:import:: java.util Map

BundledJspView
==============

.. java:package:: org.motechproject.osgi.web
   :noindex:

.. java:type:: public class BundledJspView extends JstlView implements BundleContextAware

Methods
-------
render
^^^^^^

.. java:method:: @Override public void render(Map<String, ?> model, HttpServletRequest request, HttpServletResponse response) throws RenderException
   :outertype: BundledJspView

setBundleContext
^^^^^^^^^^^^^^^^

.. java:method:: @Override public void setBundleContext(BundleContext bundleContext)
   :outertype: BundledJspView

