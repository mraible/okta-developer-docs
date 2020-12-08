---
# This file controls the links and content shown on the /pricing landing page.

component: Pricing
title: Pricing

showBreadcrumb: False

features:
  hiAvailability:
    name: 99.9% availability
  serviceAssurance:
    name: Service level assurance
  capacity:
    name: User capacity
  customApps:
    name: Custom applications
  support:
    name: Support
  authentication:
    name: Authentication
    bullets:
      - Outbound federation to custom applications
      - Social authentication
      - Group-level password policies
      - Group and application-level sign-in policies
  authorization:
    name: Authorization
    bullets:
      - 1 authorization server with 1 customizable access policy
      - OAuth 2.0 support
      - Customizable scopes and claims
      - Token revocation
  userManagement:
    name: User management
    bullets:
      - Secure user store with customizable user attributes
      - User lifecycle states (e.g. activated, suspended, deactivated)
      - Attribute mapping and
  mfa:
    name: Basic multi-factor authentication
    bullets:
      - Okta Verify
  customEmailTemplates:
    name: Customizable email templates and domains
  customSignin:
    name: Customizable sign-in and registration widget
  addons:
    name: Add-on products available

editions:
  - name: Developer
    hiAvailability: True
    serviceAssurance: False
    capacity: Up to 50K MAUs
    customApps: 5 OIDC Clients
    support: Email only
    authentication: True
    authorization: True
    userManagement: True
    mfa: True
    customEmailTemplates:
      enabled: True
      additionalNote: (paid accounts only)
    customSignin: True
    addons: False
  - name: One App
    subheading: High availability, premiere support and additional MAUs for scaling your application.
    hiAvailability: True
    serviceAssurance: True
    capacity: Unlimited
    customApps: 5 OIDC Clients
    support: True
    authentication: True
    authorization: True
    userManagement: True
    mfa: True
    customEmailTemplates:
      enabled: True
    customSignin: True
    addons: True
  - name: Enterprise
    subheading: Reliable authentication and authorization for complex environments with multiple applications.
    hiAvailability: True
    serviceAssurance: True
    capacity: Unlimited
    customApps: Unlimited OIDC and SAML applications
    support: True
    authentication: True
    authorization: True
    userManagement: True
    mfa: True
    customEmailTemplates:
      enabled: True
    customSignin: True
    addons: True

addons:
  - title: B2B Integration
    link: https://www.okta.com/pricing/?&_ga=2.233629918.1380425866.1607359849-1244033381.1605546128#api-b2b-integration
    icon: /img/icons/icon--checkmark.svg
  - title: API Access Management
    link: https://www.okta.com/pricing/?&_ga=2.267241422.1380425866.1607359849-1244033381.1605546128#api-access-management
    icon: /img/icons/icon--tool.svg
  - title: Complete MFA
    link: https://www.okta.com/pricing/?&_ga=2.263728972.1380425866.1607359849-1244033381.1605546128#api-multi-factor-authentication
    icon: /img/icons/icon--multikey.svg
  - title: Single Sign-On Integrations
    link: https://www.okta.com/pricing/?&_ga=2.263728972.1380425866.1607359849-1244033381.1605546128#api-sso-oin-apps
    icon: /img/icons/icon--lock.svg
  - title: Lifecycle Management
    link: https://www.okta.com/pricing/?&_ga=2.263728972.1380425866.1607359849-1244033381.1605546128#api-lifecycle-management
    icon: /img/icons/icon--user-profiles.svg
  - title: DynamicScale
    link: https://www.okta.com/pricing?&_ga=2.263728972.1380425866.1607359849-1244033381.1605546128#api-dynamic-scale
    icon: /img/icons/icon--highcapacity.svg
---