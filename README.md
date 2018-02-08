# Sample External Identity Provider for IdentityServer4

External identity provider provides identity to IdentityServer4.

Scenario. Admitted students need to login with, for example, admition code. You create Mvc Identity provider for let students to login into IdentityServer4. Later students can use single sign on for login into IdentityServer4 and link their single sign on login to previosly created account.

IdentityServer4 gets identity through external security provider https://github.com/kvoyk/ExternalSecurityProvider

Mvc Identity Provider uses Redis for storing authenticated users https://github.com/MicrosoftArchive/redis/releases

You can implement ILoggedUsersStorage and use your own storage or use LoggedUsersMemoryStorage.

Other samples

IdentityServer4 QuickStart_4 sample with external security provider and two additional identity providers Mvc and Cosign https://github.com/kvoyk/4_ImplicitFlowAuthenticationWithExternal

IdentityServer4 QuickStart_5 sample with external security provider and two additional identity providers Mvc and Cosign https://github.com/kvoyk/5_HybridFlowAuthenticationWithApiAccess
