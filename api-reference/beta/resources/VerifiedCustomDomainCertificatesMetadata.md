# VerifiedCustomDomainCertificatesMetadata resource type

Represents the certificate details associated with the application published through Azure Active Directory Application proxy.

### Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|thumbprint|String|The thumbprint of the certificate.<BR>Read-only|
|subjectName|String|The subject name of the certificate.<BR>Read-only|
|issuerName|String|The name of the issuer of the certificate.<BR>Read-only|
|issueDate|datetime|The date and time the certificate was issued.<BR>Read-only|
|expiryDate|datetime|The date and time the certificate will expire.<BR>Read-only|

### JSON representation

Here is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.connector"
}-->

```json
{
  "thumbprint": "String",
  "subjectName": "String",
  "issuerName": "String",
  "issueDate": "datetime",
  "expiryDate": "datetime"
}

```

<!-- uuid: de57c521-8b98-44a5-b6e3-dd7733efe847
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "VerifiedCustomDomainCertificatesMetadata resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->
