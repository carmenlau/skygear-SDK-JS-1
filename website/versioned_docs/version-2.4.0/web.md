---
id: version-2.4.0-web
title: web package
hide_title: true
original_id: web
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->


## web package

## Classes

|  Class | Description |
|  --- | --- |
|  [AuthContainer](./web.authcontainer.md) | Skygear Auth APIs. |
|  [BaseAPIClient](./web.baseapiclient.md) |  |
|  [Container](./web.container.md) | Skygear APIs container. |
|  [GlobalJSONContainerStorage](./web.globaljsoncontainerstorage.md) |  |
|  [ImageProcessingPipelineBuilder](./web.imageprocessingpipelinebuilder.md) | Image processing pipeline builder. |
|  [OIDCContainer](./web.oidccontainer.md) | Skygear Auth OIDC client APIs. |
|  [SkygearError](./web.skygearerror.md) | Skygear API error. |
|  [WebAPIClient](./web.webapiclient.md) |  |
|  [WebAssetContainer](./web.webassetcontainer.md) | Skygear Asset APIs (for web platforms). |
|  [WebAuthContainer](./web.webauthcontainer.md) | Skygear Auth APIs (for web platforms). |
|  [WebContainer](./web.webcontainer.md) | Skygear APIs container (for web platforms). |
|  [WebOIDCContainer](./web.weboidccontainer.md) | Skygear OIDC APIs (for web platforms). |

## Functions

|  Function | Description |
|  --- | --- |
|  [decodeAuthResponse(r)](./web.decodeauthresponse.md) |  |
|  [decodeError(err)](./web.decodeerror.md) |  |
|  [decodeIdentity(i)](./web.decodeidentity.md) |  |
|  [decodeQuery(query)](./web.decodequery.md) |  |
|  [decodeQueryComponent(s)](./web.decodequerycomponent.md) |  |
|  [decodeSession(s)](./web.decodesession.md) |  |
|  [decodeUser(u)](./web.decodeuser.md) |  |
|  [encodeIdentity(i)](./web.encodeidentity.md) |  |
|  [encodeQuery(query)](./web.encodequery.md) |  |
|  [encodeQueryComponent(s)](./web.encodequerycomponent.md) |  |
|  [encodeUser(u)](./web.encodeuser.md) |  |
|  [isValidationError(err)](./web.isvalidationerror.md) | Check if the provided error indicates the server failed to validate input parameters to API. |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [AuthorizeOptions](./web.authorizeoptions.md) | Auth UI authorization options |
|  [AuthResponse](./web.authresponse.md) |  |
|  [ByteArray](./web.bytearray.md) |  |
|  [ChallengeResponse](./web.challengeresponse.md) |  |
|  [ConfigureOptions](./web.configureoptions.md) |  |
|  [ContainerOptions](./web.containeroptions.md) |  |
|  [ContainerStorage](./web.containerstorage.md) |  |
|  [CustomTokenIdentity](./web.customtokenidentity.md) |  |
|  [ExtraSessionInfoOptions](./web.extrasessioninfooptions.md) |  |
|  [Identity](./web.identity.md) |  |
|  [IdentityClaims](./web.identityclaims.md) |  |
|  [ImageProcessingPipelineBuilderResizeOptions](./web.imageprocessingpipelinebuilderresizeoptions.md) |  |
|  [OAuthError](./web.oautherror.md) | OAuthError represents the oauth error response. https://tools.ietf.org/html/rfc6749\#section-4.1.2.1 |
|  [OAuthIdentity](./web.oauthidentity.md) |  |
|  [OAuthManualAuthorizationURLOptions](./web.oauthmanualauthorizationurloptions.md) |  |
|  [OAuthMobileAppAuthorizationURLOptions](./web.oauthmobileappauthorizationurloptions.md) |  |
|  [OAuthWebPopupAuthorizationURLOptions](./web.oauthwebpopupauthorizationurloptions.md) |  |
|  [OAuthWebRedirectAuthorizationURLOptions](./web.oauthwebredirectauthorizationurloptions.md) |  |
|  [PasswordIdentity](./web.passwordidentity.md) |  |
|  [PromoteOptions](./web.promoteoptions.md) | Auth UI anonymous user promotion options |
|  [Session](./web.session.md) |  |
|  [SessionUserAgent](./web.sessionuseragent.md) |  |
|  [SSOLoginOptions](./web.ssologinoptions.md) |  |
|  [StorageDriver](./web.storagedriver.md) |  |
|  [UploadAssetOptions](./web.uploadassetoptions.md) |  |
|  [User](./web.user.md) |  |
|  [ValidationError](./web.validationerror.md) |  |
|  [ValidationErrorCauseBase](./web.validationerrorcausebase.md) |  |
|  [ValidationErrorExpectationDetails](./web.validationerrorexpectationdetails.md) |  |
|  [ValidationErrorFormatDetails](./web.validationerrorformatdetails.md) |  |
|  [ValidationErrorRangeDetails](./web.validationerrorrangedetails.md) |  |

## Variables

|  Variable | Description |
|  --- | --- |
|  [defaultContainer](./web.defaultcontainer.md) | Default Skygear APIs container. |
|  [localStorageStorageDriver](./web.localstoragestoragedriver.md) |  |
|  [SkygearErrorNames](./web.skygearerrornames.md) |  |
|  [ValidationErrorKinds](./web.validationerrorkinds.md) |  |
|  [VERSION](./web.version.md) |  |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [FullOAuthAuthorizationURLOptions](./web.fulloauthauthorizationurloptions.md) |  |
|  [JSONObject](./web.jsonobject.md) |  |
|  [JSONValue](./web.jsonvalue.md) |  |
|  [OAuthAuthorizationURLOptions](./web.oauthauthorizationurloptions.md) |  |
|  [SkygearErrorName](./web.skygearerrorname.md) |  |
|  [ValidationErrorCause](./web.validationerrorcause.md) |  |
|  [ValidationErrorKind](./web.validationerrorkind.md) |  |
|  [ValidationInvalidConstantCause](./web.validationinvalidconstantcause.md) |  |
|  [ValidationInvalidEntryAmountCause](./web.validationinvalidentryamountcause.md) |  |
|  [ValidationInvalidEnumCause](./web.validationinvalidenumcause.md) |  |
|  [ValidationInvalidNumberRangeCause](./web.validationinvalidnumberrangecause.md) |  |
|  [ValidationInvalidStringFormatCause](./web.validationinvalidstringformatcause.md) |  |
|  [ValidationInvalidStringLengthCause](./web.validationinvalidstringlengthcause.md) |  |
|  [ValidationInvalidTypeCause](./web.validationinvalidtypecause.md) |  |
