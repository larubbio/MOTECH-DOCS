.. java:import:: org.apache.activemq.util URISupport

.. java:import:: org.apache.commons.validator UrlValidator

.. java:import:: org.motechproject.server.web.form StartupForm

.. java:import:: java.net URI

.. java:import:: java.net URISyntaxException

.. java:import:: java.util List

QueueURLValidator
=================

.. java:package:: org.motechproject.server.web.validator
   :noindex:

.. java:type:: public class QueueURLValidator implements AbstractValidator

   Validates presence of Queue URL and if present whether it is in expected format or not

Constructors
------------
QueueURLValidator
^^^^^^^^^^^^^^^^^

.. java:constructor:: public QueueURLValidator()
   :outertype: QueueURLValidator

QueueURLValidator
^^^^^^^^^^^^^^^^^

.. java:constructor:: public QueueURLValidator(UrlValidator urlValidator)
   :outertype: QueueURLValidator

Methods
-------
validate
^^^^^^^^

.. java:method:: @Override public void validate(StartupForm target, List<String> errors)
   :outertype: QueueURLValidator

