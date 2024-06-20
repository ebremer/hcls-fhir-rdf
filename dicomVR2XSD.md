# Sources
- [DICOM VR] (https://dicom.nema.org/medical/dicom/current/output/chtml/part05/sect_6.2.html#table_6.2-1)
- [XSD] (https://www.w3.org/TR/2004/REC-xmlschema-2-20041028/)
- [DICOM JSON] (https://dicom.nema.org/dicom/2013/output/chtml/part18/sect_F.2.html#table_F.2.3-1)

| VR                | Name                                         | Length of Value  | XSD Data Type | DICOM JSON Data Type  |
|-------------------|----------------------------------------------|------------------|---------------|-----------------|
| AE                | Application Entity                           | 16 bytes maximum | string        | string          |
| AS                | Age String                                   | 4 bytes fixed    | string        | string          |
| AT                | Attribute Tag                                | 4 bytes fixed    | string        | string          |
| CS                | Code String                                  | 16 bytes maximum | string        | string          |
| DA                | Date                                         | 8                | date          | string          |
| DS                | Decimal String                               | 16               | decimal       | string          |
| DT                | Date Time                                    | 26               | dateTime      | string          |
| FL                | Floating Point Single                        | 4                | float         | number          |
| FD                | Floating Point Double                        | 8                | double        | number          |
| IS                | Integer String                               | 12               | int           | number          |
| LO                | Long String                                  | 64               | string        | string          |
| LT                | Long Text                                    | 10240            | string        | string          |
| OB                | Other Byte                                   | N                | base64Binary  | Base64 encoded string |
| OD                | Other Double                                 | N                | base64Binary  | Base64 encoded string |
| OF                | Other Float                                  | N                | base64Binary  | Base64 encoded string |
| OL                | Other Long                                   | N                | base64Binary  | Base64 encoded string |
| OW                | Other Word                                   | N                | base64Binary  | Base64 encoded string |
| PN                | Person Name                                  | 64               | string        | string          |
| SH                | Short String                                 | 16               | string        | Object containing Person Name component groups as strings |
| SL                | Signed Long                                  | 4                | int           | number          |
| SQ                | Sequence of Items                            | N                | anyType       | Array containing DICOM JSON Objects |
| SS                | Signed Short                                 | 2                | short         | number          |
| ST                | Short Text                                   | 1024             | string        | string          |
| SV                | Signed binary integer 64 bits long           | 8 bytes          | long          | number          |
| TM                | Time                                         | 16               | time          | string          |
| UC                | Unlimited Characters                         | N                | string        | string          |
| UI                | Unique Identifier (UID)                      | 64               | string        | string          |
| UL                | Unsigned Long                                | 4                | unsignedInt   | number          |
| UN                | Unknown                                      | N                | base64Binary  | Base64 encoded string |
| UR                | URI or URL                                   | N                | anyURI        | string          |
| US                | Unsigned Short                               | 2                | unsignedShort | number          |
| UT                | Unlimited Text                               | N                | string        | string          |
| OB or OW          | Other Byte or Word                           | N                | base64Binary  | Base64 encoded string |
| US or SS          | Unsigned Short or Signed Short               | 2                | anyType       | number          |
| US or SS or OW    | Unsigned Short or Signed Short or Other Word | N                | anyType       | number          |
