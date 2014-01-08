.. java:import:: org.motechproject.tasks.domain ParameterType

.. java:import:: java.lang.annotation Documented

.. java:import:: java.lang.annotation ElementType

.. java:import:: java.lang.annotation Retention

.. java:import:: java.lang.annotation RetentionPolicy

.. java:import:: java.lang.annotation Target

TaskActionParam
===============

.. java:package:: org.motechproject.tasks.annotations
   :noindex:

.. java:type:: @Target @Retention @Documented public @interface TaskActionParam

   Marks method parameter to be treated as action parameter.

   Each parameter in the given method has to have this annotation otherwise it will be a problem with the proper execution of the channel action.

