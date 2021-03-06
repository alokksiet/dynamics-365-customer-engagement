# [Microsoft Dynamics 365 for Customer Insights](./getstart.md)
<!-- ##[About Customer Insights](./deploy/getstart2.md) -->
## [About Preview](./deploy/aboutpreview.md)
## [Known Issues](./deploy/inthisrelease.md)
## [What's New](./deploy/newfeatures.md)
<!-- ### [Overview](./deploy/overview.md) -->
### [Predictive Match](./deploy/createconflationpolicy.md)
### [Predictive Scoring](./deploy/buildmlmodel.md)
### [Segmentation](./deploy/createasegment.md)
<!-- ### [Lead Scoring](./deploy/leadscoring.md) -->

## [Set up Customer Insights](./deploy/stepbystepconfiguration.md)
### [Prerequisites](./deploy/prerequisites.md)
### [Create Your Customer Insights Hub](./deploy/createdcihub.md)
### [Add a Data Source](./deploy/adddatasource.md)
#### [Add Dynamics 365 (online) as a Data Source](./deploy/datasource365online.md)
#### [Add Azure Storage as a Data Source](./deploy/datasourceazurestorage.md)
#### [Add Exchange Online as a Data Source](./deploy/datasourceoffice365.md)
#### [Add Microsoft Social Engagement as a Data Source](./deploy/datasourcemse.md)
### [Data Modeling](./deploy/datamodeling.md)

## [Set up Customer 360](./deploy/stepbystepcustomer360.md)
## [Analyze Your Data with Power BI](./deploy/powerbi.md)
## [Set up Role-based Security](./deploy/stepbysteprolebasedsecurity.md)
## [Embed Customer Insights Widgets](./deploy/stepbystepembeddingaciwidgets.md)
### [Embed a Customer Insights View](./deploy/embedaciview.md)
### [Embed a Customer Insights View in a CRM Web Resource](./deploy/embedaciviewincrmwebresource.md)



# [Microsoft Dynamics 365 for Customer Insights Developer Guide](./dev/devguide.md) 
## [Customer Insights Architecture](./dev/architecture.md) 
## [About Customer Insights Web Services](./dev/aboutwebsvcs.md) 
## [Working with Data in Customer Insights](./dev/workingwithdata.md) 

## [Customer Insights Programming Reference](./ref/progref.md) 
### [API Requests and Responses](./ref/requestreponse.md) 
### [Customer Insights API Quick Reference](./ref/apiquickref.md) 
### [Segmentation Query Language Reference](./ref/segquerylang.md) 


### [Metadata Type Definitions](./ref/metadatadefs.md) 
#### [AuthorizationPolicy Type](./ref/types/authzpolicy.md)
#### [Connector Types](./ref/types/connector.md)
#### [ConnectorMapping Types](./ref/types/connectormapping.md)
#### [DataFormat Types](./ref/types/dataformat.md) 
#### [DataSource Type](./ref/types/datasource.md) 
#### [Field Type](./ref/types/field.md) 
#### [Hub Types](./ref/types/hub.md) 
#### [Image Types](./ref/types/images.md) 
#### [Interaction Types](./ref/types/interaction.md) 
#### [KPI Types](./ref/types/kpi.md)
#### [Link Types](./ref/types/link.md)
#### [Prediction Type](./ref/types/prediction.md) 
#### [PredictionModelStatus Type](./ref/types/predictionmodelstatus.md) 
#### [PredictionTrainingResults Types](./ref/types/predictiontrainingresults.md) 
#### [PredictiveMatchPolicy Types](./ref/types/predictivematchpolicy.md) 
#### [Profile Types](./ref/types/profile.md) 
#### [Relationship Types](./ref/types/relationship.md)
#### [Relationship Link Types](./ref/types/relationshiplink.md)
#### [Role Type](./ref/types/role.md)
#### [RoleAssignment Types](./ref/types/roleassignment.md) 
#### [Segment Types](./ref/types/segment.md)
#### [View Type](./ref/types/view.md)
#### [WidgetType Type](./ref/types/widgettype.md)

### [Azure Resource Manager (ARM) API Reference](./ref/armapiref.md) 
#### [Hub CRUD APIs](./ref/arm/hubcrud.md) 
##### [Create or Update Hub](./ref/arm/hubcreateupdate.md) 
##### [Update Hub](./ref/arm/hubupdate.md) 
##### [Get Hub](./ref/arm/hubget.md) 
##### [List Hubs](./ref/arm/hublist.md) 
##### [Delete Hub](./ref/arm/hubdelete.md) 
#### [Hub Management APIs (via ARM)](./ref/arm/hubmngnt.md) 

#### [Type Modeling APIs](./ref/arm/typemodeling.md) 
##### [Create or Update Profile Type](./ref/arm/profilecreateupdate.md) 
##### [Get Profile Type](./ref/arm/profileget.md) 
##### [Get Enriching KPIs for Profile](./ref/arm/profilegetenrichingkpis.md)
##### [List Profiles](./ref/arm/profilelist.md)
##### [Delete Profile](./ref/arm/profiledelete.md)
##### [Create or Update Interaction Type](./ref/arm/interactioncreateupdate.md) 
##### [Get Interaction Type](./ref/arm/interactionget.md) 
##### [List Interaction Types](./ref/arm/interactionlist.md) 
##### [Suggest Relationships for Interaction](./ref/arm/interactionsugrellinks.md) 
##### [Create or Update Relationship Type](./ref/arm/relationshipcreateupdate.md) 
##### [Get Relationship Type](./ref/arm/relationshipget.md) 
##### [List Relationship Types](./ref/arm/relationshiplist.md) 
##### [Delete Relationship Type](./ref/arm/relationshipdelete.md) 
##### [Create or Update Relationship Link Type](./ref/arm/relationshiplinkcreateupdate.md) 
##### [Get Relationship Link Type](./ref/arm/relationshiplinkget.md) 
##### [List Relationship Link Types](./ref/arm/relationshiplinklist.md) 
##### [Delete Relationship Link Type](./ref/arm/relationshiplinkdelete.md) 

#### [Link Management APIs](./ref/arm/linkmngnt.md) 
##### [Create or Update Link](./ref/arm/linkcreateupdate.md) 
##### [Get Link Type ](./ref/arm/linkget.md) 
##### [List Link Types](./ref/arm/linklist.md) 
##### [Delete Link](./ref/arm/linkdelete.md) 

#### [Segmentation Management APIs](./ref/arm/segmngnt.md) 
##### [Create or Update Dynamic Segment Type](./ref/arm/segdyncreateupdate.md) 
##### [Create or Update Static Segment Type](./ref/arm/segstatcreateupdate.md) 
##### [Get Segment Type](./ref/arm/segget.md) 
##### [List Segment Types](./ref/arm/seglist.md) 
##### [Delete Segment Type](./ref/arm/segdelete.md) 

#### [KPI Management APIs](./ref/arm/kpimngnt.md) 
##### [Create or Update KPI](./ref/arm/kpicreateupdate.md) 
##### [Get KPI Type](./ref/arm/kpiget.md) 
##### [List KPI Types](./ref/arm/kpilist.md) 
##### [Delete KPI](./ref/arm/kpidelete.md) 
##### [Reprocess KPI](./ref/arm/kpireprocess.md) 

#### [Predictive Scoring APIs](./ref/arm/predscoringmngnt.md) 
##### [Create or Update Prediction](./ref/arm/predscoringcreateupdate.md) 
##### [Get Prediction Type](./ref/arm/predscoringget.md) 
##### [List Prediction Types](./ref/arm/predscoringlist.md) 
##### [Delete Prediction](./ref/arm/predscoringdelete.md) 
##### [Create or Update Model Status](./ref/arm/predscoringcreateupdatemodelstatus.md) 
##### [Get Model Status](./ref/arm/predscoringgetmodelstatus.md) 
##### [Get Training Results](./ref/arm/predscoringgettrainingresults.md) 

#### [Image Management APIs](./ref/arm/imagemngnt.md) 
##### [Get Image Upload URL for a Type](./ref/arm/imagegetuploadurlmetadata.md) 
##### [Get Image Upload URL for instance Data](./ref/arm/imagegetuploadurlinstance.md) 

#### [Data Connector Management APIs](./ref/arm/dataconmngnt.md) 
##### [Create or Update Data Connector](./ref/arm/dataconcreateupdate.md) 
##### [Get Data Connector](./ref/arm/dataconget.md) 
##### [List Data Connectors](./ref/arm/dataconlist.md) 
##### [Delete Data Connector](./ref/arm/datacondelete.md) 
##### [Create or Update Data Connector Mapping](./ref/arm/dataconmapcreateupdate.md) 
##### [Get Data Connector Mapping](./ref/arm/dataconmapget.md) 
##### [List Data Connector Mappings](./ref/arm/dataconmaplist.md) 
##### [Delete Data Connector Mapping](./ref/arm/dataconmapdelete.md) 

#### [App Packaging Management APIs](./ref/arm/apppackagingmngnt.md) 
##### [Get Widget Type](./ref/arm/apppackwidgetget.md) 
##### [List Widget Types](./ref/arm/apppackwidgetlist.md) 
##### [Create or Update App View](./ref/arm/apppackviewcreateupdate.md) 
##### [Get App View](./ref/arm/apppackviewget.md) 
##### [List App Views](./ref/arm/apppackviewlist.md) 
##### [Delete App View](./ref/arm/apppackviewdelete.md) 

#### [SAS Authorization Policies Management APIs](./ref/arm/authzmngnt.md) 
##### [Create or Update SAS Policy](./ref/arm/authzpolicycreateupdate.md) 
##### [Get SAS Policy](./ref/arm/authzpolicyget.md) 
##### [List SAS Policies](./ref/arm/authzpolicylist.md) 
##### [Regenerate Primary Key of a SAS Policy](./ref/arm/authzpolicyregenprimkey.md) 

##### [Regenerate Secondary Key of a SAS Policy](./ref/arm/authzpolicyregenseckey.md) 
#### [RBAC Management APIs](./ref/arm/rbacmngnt.md) 
##### [Create or Update Role Assignment](./ref/arm/rbacroleasgncreateupdate.md) 
##### [Get Role Assignment Type](./ref/arm/rbacroleasgnget.md) 
##### [List Role Assignment Types](./ref/arm/rbacroleasgnlist.md) 
##### [Delete Role Assignment](./ref/arm/rbacroleasgndelete.md) 
##### [List Role Types](./ref/arm/rbacrolelist.md) 


### [Hub API Reference](./ref/hubapiref.md) 
#### [Hub Management APIs](./ref/hub/hubmngnt.md) 
##### [Type Modeling APIs](./ref/hub/typemodeling.md) 
###### [Create Or Update Profile Type](./ref/hub/profilecreateupdate.md) 
###### [Get Profile Type](./ref/hub/profileget.md) 
###### [Get Enriching KPIs for Profile](./ref/hub/profilegetenrichingkpis.md)
###### [List Hub Profile Types](./ref/hub/profilelist.md) 
###### [Delete Profile](./ref/hub/profiledelete.md)
###### [Create or Update Interaction Type](./ref/hub/interactioncreateupdate.md) 
###### [Get Interaction Type](./ref/hub/interactionget.md) 
###### [List Hub Interaction Types](./ref/hub/interactionlist.md) 
###### [Suggest Relationships for Interaction](./ref/hub/interactionsugrellinks.md) 
###### [Create or Update Relationship Type](./ref/hub/relationshipcreateupdate.md) 
###### [Get Relationship Type](./ref/hub/relationshipget.md) 
###### [List Relationship Types](./ref/hub/relationshiplist.md) 
###### [Delete Relationship Type](./ref/hub/relationshipdelete.md) 
###### [Create or Update Relationship Link Type](./ref/hub/relationshiplinkcreateupdate.md) 
###### [Get Relationship Link Type](./ref/hub/relationshiplinkget.md) 
###### [List Relationship Link Types](./ref/hub/relationshiplinklist.md) 
###### [Delete Relationship Link Type](./ref/hub/relationshiplinkdelete.md) 

##### [Link Management APIs](./ref/hub/linkmngnt.md) 
###### [Create or Update Link](./ref/hub/linkcreateupdate.md) 
###### [Get Link Type](./ref/hub/linkget.md) 
###### [List Link Types](./ref/hub/linklist.md) 
###### [Delete Link](./ref/hub/linkdelete.md) 

##### [Segmentation Management APIs](./ref/hub/segmngnt.md) 
###### [Create or Update Dynamic Segment Type](./ref/hub/segdyncreateupdate.md) 
###### [Create or Update Static Segment Type](./ref/hub/segstatcreateupdate.md) 
###### [Get Segment Type](./ref/hub/segget.md) 
###### [List Segment Types](./ref/hub/seglist.md) 
###### [Delete Segment Type](./ref/hub/segdelete.md) 

##### [KPI Management APIs](./ref/hub/kpimngnt.md) 
###### [Create or Update KPI](./ref/hub/kpicreateupdate.md) 
###### [Get KPI Type ](./ref/hub/kpiget.md) 
###### [List KPI Types](./ref/hub/kpilist.md) 
###### [Delete KPI](./ref/hub/kpidelete.md)
###### [Reprocess KPI](./ref/hub/kpireprocess.md) 

##### [Predictive Scoring APIs](./ref/hub/predscoringmngnt.md) 
###### [Create or Update Prediction](./ref/hub/predscoringcreateupdate.md) 
###### [Get Prediction Type](./ref/hub/predscoringget.md) 
###### [List Prediction Types](./ref/hub/predscoringlist.md) 
###### [Delete Prediction](./ref/hub/predscoringdelete.md) 
###### [Create or Update Model Status](./ref/hub/predscoringcreateupdatemodelstatus.md) 
###### [Get Model Status](./ref/hub/predscoringgetmodelstatus.md) 
###### [Get Training Results](./ref/hub/predscoringgettrainingresults.md) 

##### [Image Management APIs](./ref/hub/imagemngnt.md) 
###### [Get Image Upload URL for a Type](./ref/hub/imagegetuploadurlmetadata.md) 
###### [Get Image Upload URL for instance Data](./ref/hub/imagegetuploadurlinstance.md) 

##### [Data Connector Management APIs](./ref/hub/dataconmngnt.md) 
###### [Create or Update Data Connector](./ref/hub/dataconcreateupdate.md) 
###### [Get Data Connector](./ref/hub/dataconget.md) 
###### [List Data Connectors](./ref/hub/dataconlist.md) 
###### [Delete Data Connector](./ref/hub/datacondelete.md) 
###### [Create or Update Data Connector Mapping](./ref/hub/dataconmapcreateupdate.md) 
###### [Get Data Connector Mapping](./ref/hub/dataconmapget.md) 
###### [List Data Connector Mappings](./ref/hub/dataconmaplist.md) 
###### [Delete Data Connector Mapping](./ref/hub/dataconmapdelete.md) 
###### [Discover Salesforce Connector Tables](./ref/hub/datacondiscoversalesforce.md) 

##### [App Packaging Management APIs](./ref/hub/apppackagingmngnt.md) 
###### [Get Widget Type](./ref/hub/apppackwidgetget.md) 
###### [List Widget Types](./ref/hub/apppackwidgetlist.md) 
###### [Create or Update App View](./ref/hub/apppackviewcreateupdate.md) 
###### [Get App View](./ref/hub/apppackviewget.md) 
###### [List App Views](./ref/hub/apppackviewlist.md) 
###### [Delete App View](./ref/hub/apppackviewdelete.md) 

##### [SAS Authorization Policies Management APIs](./ref/hub/authzmngnt.md) 
###### [Create or Update SAS Policy](./ref/hub/authzpolicycreateupdate.md) 
###### [Get SAS Policy](./ref/hub/authzpolicyget.md) 
###### [List SAS Policies](./ref/hub/authzpolicylist.md) 
###### [Regenerate Primary Key of a SAS Policy](./ref/hub/authzpolicyregenprimkey.md) 
###### [Regenerate Secondary Key of a SAS Policy](./ref/hub/authzpolicyregenseckey.md) 

##### [RBAC Management APIs](./ref/hub/rbacmngnt.md) 
###### [Create or Update Role Assignment](./ref/hub/rbacroleasgncreateupdate.md) 
###### [Get Role Assignment Type](./ref/hub/rbacroleasgnget.md) 
###### [List Role Assignment Types](./ref/hub/rbacroleasgnlist.md) 
###### [Delete Role Assignment](./ref/hub/rbacroleasgndelete.md) 
###### [List Role Types](./ref/hub/rbacrolelist.md) 

##### [Predictive Matching Policy Management APIs](./ref/hub/predmatchpolmngnt.md)
###### [Create or Update Predictive Match Policy](./ref/hub/predmatchpolcreateupdate.md)
###### [Get a Predictive Match Policy Type](./ref/hub/predmatchpolget.md)
###### [List Predictive Match Policy Types](./ref/hub/predmatchpollist.md)
###### [Delete Predictive Match Policy](./ref/hub/predmatchpoldelete.md)

#### [Hub Data APIs](./ref/hubdataapiref.md) 
##### [Create Profile instance](./ref/hubdata/profilecreateinstance.md) 
##### [Get Profile Instances](./ref/hubdata/profilelistinstances.md) 
##### [Get Profile Instance by ID](./ref/hubdata/profilegetinstanceid.md) 
##### [Create Interaction Instance](./ref/hubdata/interactioncreateinstance.md) 
##### [Get Interactions Associated with a Profile Type](./ref/hubdata/interactionlistviaprofile.md) 

##### [Create Relationship instance](./ref/hubdata/relationshipcreateinstance.md)
##### [Delete Relationship instance](./ref/hubdata/relationshipdeleteinstance.md)
##### [List Relationship Instances](./ref/hubdata/relationshiplistinstance.md)

##### [List all Segment Instances](./ref/hubdata/seggetinstance.md) 
##### [List Segment Members](./ref/hubdata/seglistmembers.md) 
##### [List Added Segment Members](./ref/hubdata/seglistaddedmembers.md) 
##### [Estimate Segment Result Count](./ref/hubdata/segestimation.md) 
##### [Segmentation Query Evaluation](./ref/hubdata/segqueryeval.md) 

##### [Create Blob Bulk Ingestion Job](./ref/hubdata/bulkingestcreate.md) 
##### [Query Blob Bulk Ingestion Jobs](./ref/hubdata/bulkingestquery.md) 
##### [Query KPI Data](./ref/hubdata/kpiquerydata.md) 
##### [Get KPI data for a Profile ID](./ref/hubdata/kpigetviaprofileid.md)  
