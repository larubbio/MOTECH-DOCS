.. java:import:: ch.lambdaj Lambda

.. java:import:: org.hamcrest.beans HasPropertyWithValue

.. java:import:: org.junit Before

.. java:import:: org.junit Test

.. java:import:: org.junit.runner RunWith

.. java:import:: org.motechproject.security.authentication MotechPasswordEncoder

.. java:import:: org.motechproject.security.domain MotechUser

.. java:import:: org.motechproject.security.domain MotechUserCouchdbImpl

.. java:import:: org.motechproject.security.ex EmailExistsException

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.test.context ContextConfiguration

.. java:import:: org.springframework.test.context.junit4 SpringJUnit4ClassRunner

.. java:import:: java.util List

.. java:import:: java.util Locale

AllMotechWebUsersIT
===================

.. java:package:: org.motechproject.security.repository
   :noindex:

.. java:type:: @RunWith @ContextConfiguration public class AllMotechWebUsersIT

Methods
-------
findByUserName
^^^^^^^^^^^^^^

.. java:method:: @Test public void findByUserName()
   :outertype: AllMotechWebUsersIT

findByUserNameShouldBeCaseInsensitive
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void findByUserNameShouldBeCaseInsensitive()
   :outertype: AllMotechWebUsersIT

findByUseridShouldReturnNullIfuserNameIsNull
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void findByUseridShouldReturnNullIfuserNameIsNull()
   :outertype: AllMotechWebUsersIT

setUp
^^^^^

.. java:method:: @Before public void setUp()
   :outertype: AllMotechWebUsersIT

shouldListWebUsersByRole
^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldListWebUsersByRole()
   :outertype: AllMotechWebUsersIT

shouldNotAllowDuplicateEmails
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotAllowDuplicateEmails()
   :outertype: AllMotechWebUsersIT

shouldNotCreateNewAccountIfUserAlreadyExists
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:method:: @Test public void shouldNotCreateNewAccountIfUserAlreadyExists()
   :outertype: AllMotechWebUsersIT

