# onPremisesPublishing resource type




### Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|externalAuthenticationType|String|Details the pre-authentication setting for the application Possible values are: `passthru`, `aadPreAuthentication`.|
|externalUrl|String|The published external url for the application. For example https://intranet-contoso.msappproxy.net/  |
|internalUrl|String|The internal url of the application. For example http://intranet/|
|isOnPremPublishingEnabled|Boolean|Indicates if the application is currently being published or not.|
|isTranslateHostHeaderEnabled|Boolean|Indicates if the application should translate urls in the response headers. This includes setting the correct site for cookies.|
|verifiedCustomDomainKeyCredential|[keyCerdential](keyCerdential.md)|PFX file containing the certificate to be used with the published application. Used only for POST operations|
|verifiedCustomDomainKeyCredential|[passwordCredential](passwordCredential.md)|Password associated with the PFX file. Used only in POST operations|
|verifiedCustomDomainCertificatesMetadata|[verifiedCustomDomainCertificatesMetadata](verifiedCustomDomainCertificatesMetadata.md)|Details of the associated certificate - create a reference for this one|

### JSON representation

Here is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.onPremisesPublishing"
}-->

```json
{
  "customDomainCertificate": "String",
  "externalAuthenticationType": "String",
  "externalUrl": "String",
  "internalUrl": "String",
  "isOnPremPublishingEnabled": true,
  "isTranslateHostHeaderEnabled": true,
  "verifiedCustomDomainCertificatesMetadata" : [{"@odata.type": "microsoft.graph.verifiedCustomDomainCertificatesMetadata"}]
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "onPremisesPublishing resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->
