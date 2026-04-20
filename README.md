# AT&T (at-and-t)
AT&T is a multinational telecommunications holding company providing wireless and wireline telecommunications services, broadband, and digital entertainment to consumers and businesses worldwide. AT&T offers a suite of developer APIs spanning messaging, speech, mobile virtual network operations, business voice, wholesale service qualification, enterprise wireline ordering, and mobility management, enabling developers and enterprise partners to integrate AT&T network capabilities into applications and systems.

**URL:** [https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Telecommunications, Wireless, Wireline, Messaging, Speech, Mobile, Broadband, Enterprise

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-04-19

## APIs

### AT&T SMS API
A RESTful API enabling established businesses to broadcast SMS short code messages to AT&T subscribers in the United States. Supports sending to up to 50 recipients per call and up to 1 million messaging API calls monthly. Includes delivery status callbacks and GSMA OneAPI-compatible endpoints.

**Human URL:** [https://developer.att.com/sms](https://developer.att.com/sms)

#### Tags:

 - SMS, Messaging, Short Code, Notifications

#### Properties

- [Documentation](https://developer.att.com/sms/docs)
- [APIReference](https://developer.att.com/sms/docs/v2)
- [Authentication](https://developer.att.com/oauth-2/docs)
- [GettingStarted](https://developer.att.com/sms)
- [OpenAPI](openapi/at-and-t-sms-api.yaml)

### AT&T In-App Messaging API
A messaging API enabling applications to send, receive, update, and delete MMS and SMS messages on behalf of users with explicit consent. Supports messages to phone numbers, short codes, and email addresses across AT&T and other carriers, with inbox management and delta synchronization.

**Human URL:** [https://developer.att.com/in-app-messaging](https://developer.att.com/in-app-messaging)

#### Tags:

 - MMS, SMS, Messaging, In-App, Inbox

#### Properties

- [Documentation](https://developer.att.com/in-app-messaging/docs)
- [Authentication](https://developer.att.com/oauth-2/docs)
- [OpenAPI](openapi/at-and-t-in-app-messaging-api.yaml)

### AT&T OAuth 2.0 API
AT&T OAuth 2.0 authentication API providing access tokens for all AT&T REST APIs. Supports Authorization Code, Client Credentials, and Refresh Token grant types. Scopes include ADS, MMS, SMS, SPEECH, STTC, and TTS.

**Human URL:** [https://developer.att.com/oauth-2](https://developer.att.com/oauth-2)

#### Tags:

 - OAuth, Authentication, Authorization, Security

#### Properties

- [Documentation](https://developer.att.com/oauth-2/docs)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T MVNX API
TM Forum-aligned API suite for mobile virtual network operators (MVNOs) enabling subscriber activation, number management, porting operations, device and SIM management, subscriber profile management, service management, and policy and balance management. Follows TMF standards (622, 637, 639, 640, 654, 674, 689, 702, 716, 761).

**Human URL:** [https://devex-web.att.com/mvnx](https://devex-web.att.com/mvnx)

#### Tags:

 - MVNO, Mobile, Subscriber, TM Forum, Porting, SIM

#### Properties

- [Documentation](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [GettingStarted](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [OpenAPI](openapi/at-and-t-mvnx-api.yaml)

### AT&T Alliance Wireline APIs
Wireline business APIs enabling partners to expedite quoting, service qualification, and ordering of AT&T wireline products. Includes Quick Quote, Product Catalog, Service Qualification, Price Offer, Wireline Ordering, Order Status, AIAB (AT&T Internet Air for Business) Ordering, and Address Search APIs.

**Human URL:** [https://devex-web.att.com/alliance](https://devex-web.att.com/alliance)

#### Tags:

 - Wireline, Enterprise, Ordering, Service Qualification, Quoting

#### Properties

- [Documentation](https://devex-web.att.com/alliance)
- [GettingStarted](https://devex-web.att.com/order/docs/get-started-with-ordering-api)

## Common Properties

- [Website](https://www.att.com)
- [Portal](https://developer.att.com/s/)
- [DeveloperPortal](https://devex-web.att.com/)
- [Documentation](https://developer.att.com/s/)
- [Authentication](https://developer.att.com/oauth-2/docs)
- [Support](https://developer.att.com/support)
- [FAQ](https://developer.att.com/support/faqs/att-developer-program-and-api-platform-faqs)
- [TermsOfService](https://www.att.com/gen/general?pid=11561)
- [PrivacyPolicy](https://www.att.com/gen/privacy-policy?pid=2506)
- [SignUp](https://developer.att.com/developer/manageMyAccount.jsp)
- [GitHubOrganization](https://github.com/attdevsupport)
- [GitHubOrganization](https://github.com/att)

## Features

| Name | Description |
|------|-------------|
| OAuth 2.0 Authentication | All APIs use OAuth 2.0 with client credentials, authorization code, and refresh token flows supporting multiple API scopes. |
| SMS Short Code Messaging | Broadcast SMS short code messages to AT&T subscribers with delivery tracking and callback notifications. |
| MMS and In-App Messaging | Send and receive MMS and SMS messages with inbox management, delta synchronization, and cross-carrier support. |
| MVNO Infrastructure Services | Full MVNO lifecycle management including subscriber activation, number portability, device management, and balance management via TM Forum APIs. |
| Wireline Service Qualification and Ordering | Automated quoting, service eligibility validation, and ordering for AT&T wireline products including AVPN, IPBB, ATTPhone, and more. |

## Use Cases

| Name | Description |
|------|-------------|
| SMS Alerts and Notifications | Send security verification codes, appointment reminders, promotional offers, and customer feedback requests via SMS short code. |
| In-App Messaging Integration | Embed MMS and SMS messaging directly into mobile applications with full inbox management capabilities. |
| Mobile Virtual Network Operations | Launch and operate MVNO services using AT&T's network with automated subscriber onboarding, porting, and lifecycle management. |
| Enterprise Wireline Ordering | Automate service qualification, quoting, and order submission for enterprise connectivity services. |

## Integrations

| Name | Description |
|------|-------------|
| IBM Worklight | AT&T API Platform Adapters for IBM Worklight mobile development platform. |
| Salesforce Platform | AT&T Toolkit for Salesforce enabling speech and messaging API integration in Salesforce apps. |
| TM Forum APIs | MVNX APIs align with TM Forum Open API standards including TMF 622, 637, 639, 640, 654, 674, 689, 702, 716, and 761. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AT&T SMS API](openapi/at-and-t-sms-api.yaml)
- [AT&T In-App Messaging API](openapi/at-and-t-in-app-messaging-api.yaml)
- [AT&T MVNX API](openapi/at-and-t-mvnx-api.yaml)

### JSON Schema

- [Token Request](json-schema/sms-api-token-request-schema.json)
- [Token Response](json-schema/sms-api-token-response-schema.json)
- [Send SMS Request](json-schema/sms-api-send-sms-request-schema.json)
- [Delivery Info](json-schema/sms-api-delivery-info-schema.json)
- [Inbound SMS Message](json-schema/sms-api-inbound-sms-message-schema.json)
- [Message Summary](json-schema/in-app-messaging-api-message-summary-schema.json)
- [Message Detail](json-schema/in-app-messaging-api-message-detail-schema.json)
- [Product Order](json-schema/mvnx-api-product-order-schema.json)
- [Portability Order](json-schema/mvnx-api-portability-order-schema.json)
- [Resource](json-schema/mvnx-api-resource-schema.json)
- *(and 24 additional schema files)*

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [AT&T SMS API](capabilities/shared/sms-api.yaml) — 4 operations for SMS short code messaging
- [AT&T In-App Messaging API](capabilities/shared/in-app-messaging-api.yaml) — 5 operations for user inbox messaging
- [AT&T MVNX API](capabilities/shared/mvnx-api.yaml) — 8 operations for MVNO subscriber management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [AT&T Messaging](capabilities/messaging.yaml) | SMS API, In-App Messaging API | 8 | App Developer, Enterprise Developer |
| [AT&T MVNO Operations](capabilities/mvno-operations.yaml) | MVNX API | 8 | MVNO Operator, Telecom Engineer |

## Vocabulary

- [AT&T Vocabulary](vocabulary/at-and-t-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 12 actions, 2 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [AT&T Spectral Rules](rules/at-and-t-spectral-rules.yml) — 37 rules across 13 categories enforcing AT&T API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
