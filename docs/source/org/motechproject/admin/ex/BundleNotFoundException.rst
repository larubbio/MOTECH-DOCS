.. java:import:: org.springframework.http HttpStatus

.. java:import:: org.springframework.web.bind.annotation ResponseStatus

BundleNotFoundException
=======================

.. java:package:: org.motechproject.admin.ex
   :noindex:

.. java:type:: @ResponseStatus public class BundleNotFoundException extends RuntimeException

   An exception representing a situation when a given bundle was not found. Will cause a 404 on the UI.

Constructors
------------
BundleNotFoundException
^^^^^^^^^^^^^^^^^^^^^^^

.. java:constructor:: public BundleNotFoundException(String message)
   :outertype: BundleNotFoundException

