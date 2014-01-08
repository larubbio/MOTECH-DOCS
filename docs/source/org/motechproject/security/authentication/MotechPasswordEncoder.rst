.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.security.crypto.bcrypt BCryptPasswordEncoder

.. java:import:: org.springframework.stereotype Component

MotechPasswordEncoder
=====================

.. java:package:: org.motechproject.security.authentication
   :noindex:

.. java:type:: @Component @Qualifier public class MotechPasswordEncoder extends BCryptPasswordEncoder

Methods
-------
encodePassword
^^^^^^^^^^^^^^

.. java:method:: public String encodePassword(String rawPassword)
   :outertype: MotechPasswordEncoder

isPasswordValid
^^^^^^^^^^^^^^^

.. java:method:: public boolean isPasswordValid(String encPassword, String rawPassword)
   :outertype: MotechPasswordEncoder

