.. java:import:: org.apache.commons.collections CollectionUtils

.. java:import:: org.apache.commons.lang StringUtils

.. java:import:: org.motechproject.security.authentication MotechAccessVoter

.. java:import:: org.motechproject.security.authentication MotechLogoutSuccessHandler

.. java:import:: org.motechproject.security.authentication MotechRestBasicAuthenticationEntryPoint

.. java:import:: org.motechproject.security.constants SecurityConfigConstants

.. java:import:: org.motechproject.security.domain MotechURLSecurityRule

.. java:import:: org.motechproject.security.ex SecurityConfigException

.. java:import:: org.motechproject.server.config SettingsFacade

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: org.springframework.beans.factory.annotation Autowired

.. java:import:: org.springframework.beans.factory.annotation Qualifier

.. java:import:: org.springframework.security.access AccessDecisionManager

.. java:import:: org.springframework.security.access AccessDecisionVoter

.. java:import:: org.springframework.security.access ConfigAttribute

.. java:import:: org.springframework.security.access SecurityConfig

.. java:import:: org.springframework.security.access.vote AffirmativeBased

.. java:import:: org.springframework.security.access.vote AuthenticatedVoter

.. java:import:: org.springframework.security.access.vote RoleVoter

.. java:import:: org.springframework.security.authentication AuthenticationManager

.. java:import:: org.springframework.security.openid OpenIDAuthenticationFilter

.. java:import:: org.springframework.security.web AuthenticationEntryPoint

.. java:import:: org.springframework.security.web DefaultSecurityFilterChain

.. java:import:: org.springframework.security.web SecurityFilterChain

.. java:import:: org.springframework.security.web.access ExceptionTranslationFilter

.. java:import:: org.springframework.security.web.access.channel ChannelDecisionManager

.. java:import:: org.springframework.security.web.access.channel ChannelProcessingFilter

.. java:import:: org.springframework.security.web.access.intercept DefaultFilterInvocationSecurityMetadataSource

.. java:import:: org.springframework.security.web.access.intercept FilterInvocationSecurityMetadataSource

.. java:import:: org.springframework.security.web.access.intercept FilterSecurityInterceptor

.. java:import:: org.springframework.security.web.authentication AnonymousAuthenticationFilter

.. java:import:: org.springframework.security.web.authentication UsernamePasswordAuthenticationFilter

.. java:import:: org.springframework.security.web.authentication.logout LogoutFilter

.. java:import:: org.springframework.security.web.authentication.logout LogoutHandler

.. java:import:: org.springframework.security.web.authentication.logout SecurityContextLogoutHandler

.. java:import:: org.springframework.security.web.authentication.www BasicAuthenticationFilter

.. java:import:: org.springframework.security.web.context HttpSessionSecurityContextRepository

.. java:import:: org.springframework.security.web.context SecurityContextPersistenceFilter

.. java:import:: org.springframework.security.web.context SecurityContextRepository

.. java:import:: org.springframework.security.web.savedrequest HttpSessionRequestCache

.. java:import:: org.springframework.security.web.savedrequest RequestCache

.. java:import:: org.springframework.security.web.savedrequest RequestCacheAwareFilter

.. java:import:: org.springframework.security.web.servletapi SecurityContextHolderAwareRequestFilter

.. java:import:: org.springframework.security.web.session SessionManagementFilter

.. java:import:: org.springframework.security.web.util AntPathRequestMatcher

.. java:import:: org.springframework.security.web.util AnyRequestMatcher

.. java:import:: org.springframework.security.web.util RequestMatcher

.. java:import:: org.springframework.stereotype Component

.. java:import:: javax.servlet Filter

.. java:import:: java.security SecureRandom

.. java:import:: java.util ArrayList

.. java:import:: java.util Collection

.. java:import:: java.util LinkedHashMap

.. java:import:: java.util List

.. java:import:: java.util Map

SecurityRuleBuilder
===================

.. java:package:: org.motechproject.security.builder
   :noindex:

.. java:type:: @Component public class SecurityRuleBuilder

   The security rule builder is responsible for building a SecurityFilterChain, which consists of a matcher pattern and a list of Spring security filters. The filters are created and configured base upon the security rule's settings.

Fields
------
NO_METHODS_REQUIRED_EXCEPTION_MESSAGE
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String NO_METHODS_REQUIRED_EXCEPTION_MESSAGE
   :outertype: SecurityRuleBuilder

NO_PATTERN_EXCEPTION_MESSAGE
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String NO_PATTERN_EXCEPTION_MESSAGE
   :outertype: SecurityRuleBuilder

NO_PROTOCOL_EXCEPTION_MESSAGE
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String NO_PROTOCOL_EXCEPTION_MESSAGE
   :outertype: SecurityRuleBuilder

NO_SUPPORTED_SCHEMES_EXCEPTION_MESSAGE
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. java:field:: public static final String NO_SUPPORTED_SCHEMES_EXCEPTION_MESSAGE
   :outertype: SecurityRuleBuilder

Methods
-------
buildSecurityChain
^^^^^^^^^^^^^^^^^^

.. java:method:: public synchronized SecurityFilterChain buildSecurityChain(MotechURLSecurityRule securityRule, String method)
   :outertype: SecurityRuleBuilder

