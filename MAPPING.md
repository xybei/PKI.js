This file provides a mapping from PKIjs v1 (based on ES5) and PKIjs v2 (based on ES6) class names. This is intended to help with the migration from the older version to the newer version.

| Old class name | New class name |
|----------------|----------------|
| TIME | Time |
| GENERAL_NAME | GeneralName |
| GENERAL_NAMES | GeneralNames |
| ALGORITHM_IDENTIFIER | AlgorithmIdentifier |
| RSAPublicKey | RSAPublicKey |
| OtherPrimeInfo | OtherPrimeInfo |
| RSAPrivateKey | RSAPrivateKey |
| RSASSA_PSS_params | RSASSAPSSParams |
| PUBLIC_KEY_INFO | PublicKeyInfo |
| ATTR_TYPE_AND_VALUE | AttributeTypeAndValue |
| RDN | RelativeDistinguishedNames |
| AuthorityKeyIdentifier | AuthorityKeyIdentifier |
| PrivateKeyUsagePeriod | PrivateKeyUsagePeriod |
| AltName | AltName |
| SubjectDirectoryAttributes | SubjectDirectoryAttributes |
| PolicyMapping | PolicyMapping |
| PolicyMappings | PolicyMappings |
| GeneralSubtree | GeneralSubtree |
| NameConstraints | NameConstraints |
| BasicConstraints | BasicConstraints |
| PolicyQualifierInfo | PolicyQualifierInfo |
| PolicyInformation | PolicyInformation |
| CertificatePolicies | CertificatePolicies |
| PolicyConstraints | PolicyConstraints |
| ExtKeyUsage | ExtKeyUsage |
| DistributionPoint | DistributionPoint |
| CRLDistributionPoints | CRLDistributionPoints |
| AccessDescription | AccessDescription |
| InfoAccess | InfoAccess |
| IssuingDistributionPoint | IssuingDistributionPoint |
| EXTENSION | Extension |
| EXTENSIONS | Extensions |
| CERT | Certificate |
| REV_CERT | RevokedCertificate |
| CRL | CertificateRevocationList |
| ATTRIBUTE | Attribute |
| PKCS10 | CertificationRequest |
| PKCS8 | PrivateKeyInfo |
| CERT_CHAIN | CertificateChainValidationEngine |
| CMS_CONTENT_INFO | ContentInfo |
| OtherCertificateFormat | OtherCertificateFormat |
| OtherRevocationInfoFormat | OtherRevocationInfoFormat |
| CMS_CERTIFICATE_SET | CertificateSet |
| CMS_REVOCATION_INFO_CHOICES | RevocationInfoChoices |
| IssuerAndSerialNumber | IssuerAndSerialNumber |
| cms.Attribute | Attribute |
| RSAES_OAEP_params | RSAESOAEPParams |
| PBKDF2_params | PBKDF2Params |
| PBES2_params | PBES2Params |
| SignedUnsignedAttributes | SignedUnsignedAttributes |
| CMS_SIGNER_INFO | SignerInfo |
| EncapsulatedContentInfo | EncapsulatedContentInfo |
| CMS_SIGNED_DATA | SignedData |
| ECC_CMS_SharedInfo | ECCCMSSharedInfo |
| RecipientIdentifier | RecipientIdentifier |
| KeyTransRecipientInfo | KeyTransRecipientInfo |
| OriginatorPublicKey | OriginatorPublicKey |
| OriginatorIdentifierOrKey | OriginatorIdentifierOrKey |
| OtherKeyAttribute | OtherKeyAttribute |
| RecipientKeyIdentifier | RecipientKeyIdentifier |
| KeyAgreeRecipientIdentifier | KeyAgreeRecipientIdentifier |
| RecipientEncryptedKey | RecipientEncryptedKey |
| RecipientEncryptedKeys | RecipientEncryptedKeys |
| KeyAgreeRecipientInfo | KeyAgreeRecipientInfo |
| KEKIdentifier | KEKIdentifier |
| KEKRecipientInfo | KEKRecipientInfo |
| PasswordRecipientinfo | PasswordRecipientinfo |
| OtherRecipientInfo | OtherRecipientInfo |
| CMS_RECIPIENT_INFO | RecipientInfo |
| OriginatorInfo | OriginatorInfo |
| EncryptedContentInfo | EncryptedContentInfo |
| CMS_ENVELOPED_DATA | EnvelopedData |
| CMS_ENCRYPTED_DATA | EncryptedData |
| CertID | CertID |
| Request | Request |
| TBSRequest | TBSRequest |
| Signature | Signature |
| OCSP_REQUEST | OCSPRequest |
| ResponseBytes | ResponseBytes |
| OCSP_RESPONSE | OCSPResponse |
| SingleResponse | SingleResponse |
| ResponseData | ResponseData |
| OCSP_BASIC_RESPONSE | BasicOCSPResponse |
| MessageImprint | MessageImprint |
| TSP_REQUEST | TimeStampReq |
| Accuracy | Accuracy |
| TST_INFO | TSTInfo |
| PKIStatusInfo | PKIStatusInfo |
| TSP_RESPONSE | TimeStampResp |