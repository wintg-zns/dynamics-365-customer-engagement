---
title: "Microsoft Dynamics 365 Customer Engagement adx_weblink EntityType Reference | MicrosoftDocs"
ms.date: "2017-07-10"
ms.service: "crm-online"
ms.topic: "reference"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: 2f531b01-33ed-4939-a637-c73699f76c6f
author: "jimdaly"
ms.author: "jdaly"
manager: "jdaly"
meta-description: "Reference information about the Web API adx_weblink entitytype."
---
# adx_weblink EntityType
<table>
<tr><td><b>Description:</b></td><td>[!INCLUDE[./descriptions/adx_weblink.md](./descriptions/adx_weblink.md)]</td></tr>
<tr><td><b>Entity Set path:</b></td><td>[!include[current-web-api-base-uri.md](../../includes/current-web-api-base-uri.md)]adx_weblinks </td></tr>
<tr><td><b>Base Type:</b></td><td>[crmbaseentity EntityType](crmbaseentity.md)</td></tr>
<tr><td><b>Display Name:</b></td><td>Web Link</td></tr>
<tr><td><b>Primary Key:</b></td><td>adx_weblinkid</td></tr>
<tr><td><b>Primary Name Attribute:</b></td><td>adx_name</td></tr>
<tr><td><b>Operations supported:</b></td><td>POST,GET,PATCH,DELETE</td></tr>
</table>
  
The adx_weblink entitytype has no functions or actions bound to it.

## Properties
Properties represent fields of data stored in the entity. Some properties are read-only. 


|Name|Type|Details|  
|----|----|-------|  
|adx_createdbyipaddress|Edm.String|**Display Name**: Created By IP Address<br />|
|adx_createdbyusername|Edm.String|**Display Name**: Created By Username<br />|
|adx_description|Edm.String|**Display Name**: Description<br />|
|adx_disablepagevalidation|Edm.Boolean|**Display Name**: Disable Page Validation<br />**Default Options**:<br /><table><thead><td>**Value**</td><td>**Label**</td></thead><tbody><tr><td>1</td><td>Yes</td></tr><tr><td>0</td><td>No</td></tr><tbody></table>|
|adx_displayimageonly|Edm.Boolean|**Display Name**: Display Image Only<br />**Default Options**:<br /><table><thead><td>**Value**</td><td>**Label**</td></thead><tbody><tr><td>1</td><td>Yes</td></tr><tr><td>0</td><td>No</td></tr><tbody></table>|
|adx_displayorder|Edm.Int32|**Display Name**: Display Order<br />|
|adx_displaypagechildlinks|Edm.Boolean|**Display Name**: Display Page Child Links<br />**Description**: Select whether to display the children of the page as child links for this link.<br />**Default Options**:<br /><table><thead><td>**Value**</td><td>**Label**</td></thead><tbody><tr><td>1</td><td>Yes</td></tr><tr><td>0</td><td>No</td></tr><tbody></table>|
|adx_externalurl|Edm.String|**Display Name**: External Url<br />|
|adx_imagealttext|Edm.String|**Display Name**: Image Alt Text<br />|
|adx_imageheight|Edm.Int32|**Display Name**: Image Height<br />|
|adx_imageurl|Edm.String|**Display Name**: Image Url<br />|
|adx_imagewidth|Edm.Int32|**Display Name**: Image Width<br />|
|adx_modifiedbyipaddress|Edm.String|**Display Name**: Modified By IP Address<br />|
|adx_modifiedbyusername|Edm.String|**Display Name**: Modified By Username<br />|
|adx_name|Edm.String|**Display Name**: Name<br />**Description**: Shows the name of the custom entity.<br />|
|adx_openinnewwindow|Edm.Boolean|**Display Name**: Open In New Window<br />**Default Options**:<br /><table><thead><td>**Value**</td><td>**Label**</td></thead><tbody><tr><td>1</td><td>Yes</td></tr><tr><td>0</td><td>No</td></tr><tbody></table>|
|adx_robotsfollowlink|Edm.Boolean|**Display Name**: Robots Follow Link<br />**Default Options**:<br /><table><thead><td>**Value**</td><td>**Label**</td></thead><tbody><tr><td>1</td><td>Yes</td></tr><tr><td>0</td><td>No</td></tr><tbody></table>|
|adx_weblinkid|Edm.Guid|**Display Name**: Web Link<br />**Description**: Unique identifier for entity instances<br />|
|createdon|Edm.DateTimeOffset|**Display Name**: Created On<br />**Description**: Shows when the record was created.<br />Read-only<br />|
|importsequencenumber|Edm.Int32|**Display Name**: Import Sequence Number<br />**Description**: Shows the sequence number of the import that created this record.<br />|
|modifiedon|Edm.DateTimeOffset|**Display Name**: Modified On<br />**Description**: Shows when the record was updated.<br />Read-only<br />|
|overriddencreatedon|Edm.DateTimeOffset|**Display Name**: Record Created On<br />**Description**: Shows when the record was migrated.<br />|
|statecode|Edm.Int32|**Display Name**: Status<br />**Description**: Status of the Web Link<br />**Default Options**:<br /><table><thead><td>**Value**</td><td>**Label**</td></thead><tbody><tr><td>0</td><td>Active</td></tr><tr><td>1</td><td>Inactive</td></tr><tbody></table>|
|statuscode|Edm.Int32|**Display Name**: Status Reason<br />**Description**: Reason for the status of the Web Link<br />**Default Options**:<br /><table><thead><td>**Value**</td><td>**Label**</td></thead><tbody><tr><td>1</td><td>Active</td></tr><tr><td>2</td><td>Inactive</td></tr><tbody></table>|
|timezoneruleversionnumber|Edm.Int32|**Display Name**: Time Zone Rule Version Number<br />**Description**: For internal use only.<br />|
|utcconversiontimezonecode|Edm.Int32|**Display Name**: UTC Conversion Time Zone Code<br />**Description**: Shows the time zone code that was in use when the record was created.<br />|
|versionnumber|Edm.Int64|**Display Name**: Version Number<br />**Description**: Version Number<br />Read-only<br />|

## Lookup Properties
Lookup properties are read-only, computed properties which contain entity primary key Edm.Guid data for one or more corresponding single-valued navigation properties. More information: [Lookup properties](https://msdn.microsoft.com/library/mt607990.aspx#bkmk_lookupProperties) and [Retrieve data about lookup properties](https://msdn.microsoft.com/library/gg334767.aspx#bkmk_lookupProperty).


|Name|Single-valued navigation property|Description|  
|----|---------------------------------|-----------|  
|_adx_pageid_value|adx_pageid<br />|Unique identifier for Web Page associated with Web Link.|
|_adx_parentweblinkid_value|adx_parentweblinkid<br />|Unique identifier for parent Web Link associated with Web Link.|
|_adx_publishingstateid_value|adx_publishingstateid<br />|Unique identifier for Publishing State associated with Web Link.|
|_adx_weblinksetid_value|adx_weblinksetid<br />|Unique identifier for Web Link Set associated with Web Link.|
|_createdby_value|createdby<br />|Shows the user who created the record.|
|_createdonbehalfby_value|createdonbehalfby<br />|Shows who created the record on behalf of another user.|
|_modifiedby_value|modifiedby<br />|Shows the user who updated the record.|
|_modifiedonbehalfby_value|modifiedonbehalfby<br />|Shows who last updated the record on behalf of another user.|
|_ownerid_value|ownerid<br />|Shows the owner ID.|
|_owningbusinessunit_value|owningbusinessunit<br />|Unique identifier for the business unit that owns the record|
|_owningteam_value|owningteam<br />|Unique identifier for the team that owns the record.|
|_owninguser_value|owninguser<br />|Unique identifier for the user that owns the record.|


## Single-valued navigation properties
Single-valued navigation properties represent lookup fields where a single entity can be referenced. Each single-valued navigation property has a corresponding partner collection-valued navigation property on the related entity.


|Name|Type|Partner|  
|----|----|-------|  
|adx_pageid|[adx_webpage EntityType](adx_webpage.md)|adx_webpage_weblink|
|adx_parentweblinkid|[adx_weblink EntityType](adx_weblink.md)|adx_weblink_weblink|
|adx_publishingstateid|[adx_publishingstate EntityType](adx_publishingstate.md)|adx_publishingstate_weblink|
|adx_weblinksetid|[adx_weblinkset EntityType](adx_weblinkset.md)|adx_weblinkset_weblink|
|createdby|[systemuser EntityType](systemuser.md)|lk_adx_weblink_createdby|
|createdonbehalfby|[systemuser EntityType](systemuser.md)|lk_adx_weblink_createdonbehalfby|
|modifiedby|[systemuser EntityType](systemuser.md)|lk_adx_weblink_modifiedby|
|modifiedonbehalfby|[systemuser EntityType](systemuser.md)|lk_adx_weblink_modifiedonbehalfby|
|ownerid|[principal EntityType](principal.md)|owner_adx_weblink|
|owningbusinessunit|[businessunit EntityType](businessunit.md)|business_unit_adx_weblink|
|owningteam|[team EntityType](team.md)|team_adx_weblink|
|owninguser|[systemuser EntityType](systemuser.md)|user_adx_weblink|

## Collection-valued navigation properties
Collection-valued navigation properties represent collections of entities which may represent either a one-to-many (1:N) or many-to-many (N:N) relationship between the entities.


|Name|Type|Partner|  
|----|----|-------|  
|adx_weblink_Annotations|[annotation EntityType](annotation.md)|objectid_adx_weblink|  
|adx_weblink_AsyncOperations|[asyncoperation EntityType](asyncoperation.md)|regardingobjectid_adx_weblink|  
|adx_weblink_BulkDeleteFailures|[bulkdeletefailure EntityType](bulkdeletefailure.md)|regardingobjectid_adx_weblink|  
|adx_weblink_SyncErrors|[syncerror EntityType](syncerror.md)|regardingobjectid_adx_weblink|  
|adx_weblink_weblink|[adx_weblink EntityType](adx_weblink.md)|adx_parentweblinkid|  

## Operations
The following operations can be used with the adx_weblink entity type.


|Name|Binding|Description|  
|----|-------|-----------|  
|[GrantAccess Action](../actions/grantaccess.md)|Not Bound|[!INCLUDE[../actions/descriptions/grantaccess.md](../actions/descriptions/grantaccess.md)]|  
|[IsValidStateTransition Function](../functions/isvalidstatetransition.md)|Not Bound|[!INCLUDE[../functions/descriptions/isvalidstatetransition.md](../functions/descriptions/isvalidstatetransition.md)]|  
|[ModifyAccess Action](../actions/modifyaccess.md)|Not Bound|[!INCLUDE[../actions/descriptions/modifyaccess.md](../actions/descriptions/modifyaccess.md)]|  
|[RetrievePrincipalAccess Function](../functions/retrieveprincipalaccess.md)|Not Bound|[!INCLUDE[../functions/descriptions/retrieveprincipalaccess.md](../functions/descriptions/retrieveprincipalaccess.md)]|  
|[RetrieveSharedPrincipalsAndAccess Function](../functions/retrievesharedprincipalsandaccess.md)|Not Bound|[!INCLUDE[../functions/descriptions/retrievesharedprincipalsandaccess.md](../functions/descriptions/retrievesharedprincipalsandaccess.md)]|  
|[RevokeAccess Action](../actions/revokeaccess.md)|Not Bound|[!INCLUDE[../actions/descriptions/revokeaccess.md](../actions/descriptions/revokeaccess.md)]|  

## Solutions
The following solutions include the adx_weblink entity type.


|Name|Description |  
|----|------------|  
|[Dynamics 365 Portals - Portal Base Solution](../solutions/microsoftcrmportalbase.md)|[!INCLUDE[../solutions/descriptions/microsoftcrmportalbase.md](../solutions/descriptions/microsoftcrmportalbase.md)]|  
|[Dynamics 365 Portals - Portal Dependencies Solution](../solutions/microsoftcrmportaldependencies.md)|[!INCLUDE[../solutions/descriptions/microsoftcrmportaldependencies.md](../solutions/descriptions/microsoftcrmportaldependencies.md)]|    

[!INCLUDE[./remarks/adx_weblink.md](./remarks/adx_weblink.md)]

### See also  
 [Use the Microsoft Dynamics CRM Web API](https://msdn.microsoft.com/library/mt593051.aspx)<br />
 [Web API EntityType Reference](../entitytypereference.md)<br />
 [Web API Action Reference](../actionreference.md)<br />
 [Web API Function Reference](../functionreference.md)<br />
 [Web API Query Function Reference](../queryfunctionreference.md)<br />
 [Web API EnumType Reference](../enumtypereference.md)<br />
 [Web API ComplexType Reference](../complextypereference.md)<br />
 [Web API Metadata EntityType Reference](../entitytypereference.md)<br />
 [Web API Solutions Reference](../solutionreference.md)<br />