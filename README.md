# Microsoft Graph Delegated API Entra Roles

The following table represents the least privileged roles for each Microsoft Graph API permission in the delegated context. This list was orginally created by AI based on maching the API description to the most appropriate description of the Entra Role. ***No official mapping by Microsoft exists yet.***

***Results may not be entirely accurate, please submit a PR correcting anything as you find it. The purpose of this list is to map to built-in Entra roles, not custom roles.***

- Created by Daniel Bradley - [LinkedIn](https://www.linkedin.com/in/danielbradley2/)
- Generated using the [psaisuite](https://github.com/dfinke/psaisuite) PowerShell module by Doug Finke

<table class="table table-bordered table-hover table-condensed">
<thead><tr><th title="Field #1">id</th>
<th title="Field #2">value</th>
<th title="Field #3">LeastPrivilegeRole</th>
<th title="Field #4">adminConsentDescription</th>
<th title="Field #5">adminConsentDisplayName</th>
</tr></thead>
<tbody><tr>
<td>ebfcd32b-babb-40f4-a14b-42706e83bd28</td>
<td>AccessReview.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read access reviews, reviewers, decisions and settings that the signed-in user has access to in the organization.</td>
<td>Read all access reviews that user can access</td>
</tr>
<tr>
<td>e4aa47b9-9a69-4109-82ed-36ec70d85ff1</td>
<td>AccessReview.ReadWrite.All</td>
<td>Identity Governance Administrator</td>
<td>Allows the app to read, update, delete and perform actions on access reviews, reviewers, decisions and settings that the signed-in user has access to in the organization.</td>
<td>Manage all access reviews that user can access</td>
</tr>
<tr>
<td>5af8c3f5-baca-439a-97b0-ea58a435e269</td>
<td>AccessReview.ReadWrite.Membership</td>
<td>Compliance Administrator</td>
<td>Allows the app to read, update, delete and perform actions on access reviews, reviewers, decisions and settings for group and app memberships that the signed-in user has access to in the organization.</td>
<td>Manage access reviews for group and app memberships</td>
</tr>
<tr>
<td>3361d15d-be43-4de6-b441-3c746d05163d</td>
<td>AdministrativeUnit.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read administrative units and administrative unit membership on behalf of the signed-in user.</td>
<td>Read administrative units</td>
</tr>
<tr>
<td>7b8a2d34-6b3f-4542-a343-54651608ad81</td>
<td>AdministrativeUnit.ReadWrite.All</td>
<td>User Administrator</td>
<td>Allows the app to create, read, update, and delete administrative units and manage administrative unit membership on behalf of the signed-in user.</td>
<td>Read and write administrative units</td>
</tr>
<tr>
<td>af2819c9-df71-4dd3-ade7-4d7c9dc653b7</td>
<td>Agreement.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read terms of use agreements on behalf of the signed-in user.</td>
<td>Read all terms of use agreements</td>
</tr>
<tr>
<td>ef4b5d93-3104-4664-9053-a5c49ab44218</td>
<td>Agreement.ReadWrite.All</td>
<td>Compliance Administrator</td>
<td>Allows the app to read and write terms of use agreements on behalf of the signed-in user.</td>
<td>Read and write all terms of use agreements</td>
</tr>
<tr>
<td>0b7643bb-5336-476f-80b5-18fbfbc91806</td>
<td>AgreementAcceptance.Read</td>
<td>Compliance Administrator</td>
<td>Allows the app to read terms of use acceptance statuses on behalf of the signed-in user.</td>
<td>Read user terms of use acceptance statuses</td>
</tr>
<tr>
<td>a66a5341-e66e-4897-9d52-c2df58c2bfb9</td>
<td>AgreementAcceptance.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read terms of use acceptance statuses on behalf of the signed-in user.</td>
<td>Read terms of use acceptance statuses that user can access</td>
</tr>
<tr>
<td>1b6ff35f-31df-4332-8571-d31ea5a4893f</td>
<td>APIConnectors.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read the API connectors used in user authentication flows, on behalf of the signed-in user.</td>
<td>Read API connectors for authentication flows</td>
</tr>
<tr>
<td>c67b52c5-7c69-48b6-9d48-7b3af3ded914</td>
<td>APIConnectors.ReadWrite.All</td>
<td>External ID User Flow Administrator</td>
<td>Allows the app to read, create and manage the API connectors used in user authentication flows, on behalf of the signed-in user.</td>
<td>Read and write API connectors for authentication flows</td>
</tr>
<tr>
<td>1ca167d5-1655-44a1-8adf-1414072e1ef9</td>
<td>AppCatalog.ReadWrite.All</td>
<td>Application Administrator</td>
<td>Allows the app to create, read, update, and delete apps in the app catalogs.</td>
<td>Read and write to all app catalogs</td>
</tr>
<tr>
<td>af281d3a-030d-4122-886e-146fb30a0413</td>
<td>AppCertTrustConfiguration.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read the trusted certificate authority configuration which can be used to restrict application certificates based on their issuing authority, on behalf of the signed-in user.</td>
<td>Read the trusted certificate authority configuration for applications</td>
</tr>
<tr>
<td>4bae2ed4-473e-4841-a493-9829cfd51d48</td>
<td>AppCertTrustConfiguration.ReadWrite.All</td>
<td>Security Administrator</td>
<td>Allows the app to create, read, update and delete the trusted certificate authority configuration which can be used to restrict application certificates based on their issuing authority, on behalf of the signed-in user.</td>
<td>Read and write the trusted certificate authority configuration for applications</td>
</tr>
<tr>
<td>ffa91d43-2ad8-45cc-b592-09caddeb24bb</td>
<td>Application-RemoteDesktopConfig.ReadWrite.All</td>
<td>Application Administrator</td>
<td>Allows the app to read and write other apps&#39; remote desktop security configuration, on behalf of the signed-in user.</td>
<td>Read and write the remote desktop security configuration for apps</td>
</tr>
<tr>
<td>c79f8feb-a9db-4090-85f9-90d820caa0eb</td>
<td>Application.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read applications and service principals on behalf of the signed-in user.</td>
<td>Read applications</td>
</tr>
<tr>
<td>bdfbf15f-ee85-4955-8675-146e8e5296b5</td>
<td>Application.ReadWrite.All</td>
<td>Cloud Application Administrator</td>
<td>Allows the app to create, read, update and delete applications and service principals on behalf of the signed-in user. Does not allow management of consent grants.</td>
<td>Read and write all applications</td>
</tr>
<tr>
<td>84bccea3-f856-4a8a-967b-dbe0a3d53a64</td>
<td>AppRoleAssignment.ReadWrite.All</td>
<td>Cloud Application Administrator</td>
<td>Allows the app to manage permission grants for application permissions to any API (including Microsoft Graph) and application assignments for any app, on behalf of the signed-in user.</td>
<td>Manage app permission grants and app role assignments</td>
</tr>
<tr>
<td>b0df437d-d341-4df0-aa3e-89ca81a1207f</td>
<td>ApprovalSolution.Read</td>
<td>Compliance Data Administrator</td>
<td>Allows the app to read approvals on behalf of the signed-in user.</td>
<td>Read approvals</td>
</tr>
<tr>
<td>6768d3af-4562-48ff-82d2-c5e19eb21b9c</td>
<td>ApprovalSolution.ReadWrite</td>
<td>Identity Governance Administrator</td>
<td>Allows the app to provision, read, create, and respond to approvals on behalf of the signed-in user.</td>
<td>Read, create, and respond to approvals</td>
</tr>
<tr>
<td>89d944f2-2011-44ad-830c-aa9bf5ef2319</td>
<td>ApprovalSolutionResponse.ReadWrite</td>
<td>Compliance Administrator</td>
<td>Allows the app to read and respond to approvals on behalf of the signed-in user.</td>
<td>Read and respond to approvals assigned to the current user</td>
</tr>
<tr>
<td>104a7a4b-ca76-4677-b7e7-2f4bc482f381</td>
<td>AttackSimulation.Read.All</td>
<td>Attack Simulation Administrator</td>
<td>Allows the app to read attack simulation and training data for an organization for the signed-in user.</td>
<td>Read attack simulation data of an organization</td>
</tr>
<tr>
<td>e4c9e354-4dc5-45b8-9e7c-e1393b0b1a20</td>
<td>AuditLog.Read.All</td>
<td>Reports Reader</td>
<td>Allows the app to read and query your audit log activities, on behalf of the signed-in user.</td>
<td>Read audit log data</td>
</tr>
<tr>
<td>ba78b16f-1e01-41b6-89ca-73e0a32b304c</td>
<td>AuditLogsQuery-CRM.Read.All</td>
<td>Reports Reader</td>
<td>Allows the app to read and query audit logs from Dynamics CRM workload, on behalf of the signed-in user.</td>
<td>Read audit logs data from Dynamics CRM workload</td>
</tr>
<tr>
<td>ee3409fe-617f-43cf-bd1e-fc8b38049e69</td>
<td>AuditLogsQuery-Endpoint.Read.All</td>
<td>Reports Reader</td>
<td>Allows the app to read and query audit logs from Endpoint Data Loss Prevention workload, on behalf of the signed-in user.</td>
<td>Read audit logs data from Endpoint Data Loss Prevention workload</td>
</tr>
<tr>
<td>5ff2f415-e0f1-4d11-bfd0-6d87c0f667fd</td>
<td>AuditLogsQuery-Entra.Read.All</td>
<td>Reports Reader</td>
<td>Allows the app to read and query audit logs from Entra (Azure AD) workload, on behalf of the signed-in user.</td>
<td>Read audit logs data from Entra (Azure AD) workload</td>
</tr>
<tr>
<td>6c8c71d2-c7e1-45b0-ac6d-1d2724fba6ae</td>
<td>AuditLogsQuery-Exchange.Read.All</td>
<td>Reports Reader</td>
<td>Allows the app to read and query audit logs from Exchange workload, on behalf of a signed-in user.</td>
<td>Read audit logs data from Exchange workload</td>
</tr>
<tr>
<td>4a72c235-a50d-4870-b598-fd88fd1fa074</td>
<td>AuditLogsQuery-OneDrive.Read.All</td>
<td>Reports Reader</td>
<td>Allows the app to read and query audit logs from OneDrive workload, on behalf of a signed-in user.</td>
<td>Read audit logs data from OneDrive workload</td>
</tr>
<tr>
<td>30630b65-ed12-4a81-9130-e3a964109fae</td>
<td>AuditLogsQuery-SharePoint.Read.All</td>
<td>Reports Reader</td>
<td>Allows the app to read and query audit logs from SharePoint workload, on behalf of a signed-in user.</td>
<td>Read audit logs data from SharePoint workload</td>
</tr>
<tr>
<td>1d9e7ac3-0eca-442c-82f9-e92625af6e6d</td>
<td>AuditLogsQuery.Read.All</td>
<td>Reports Reader</td>
<td>Allows the app to read and query audit logs from all services, on behalf of a signed-in user</td>
<td>Read audit logs data from all services</td>
</tr>
<tr>
<td>57b030f1-8c35-469c-b0d9-e4a077debe70</td>
<td>AuthenticationContext.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read all authentication context information in your organization on behalf of the signed-in user.</td>
<td>Read all authentication context information</td>
</tr>
<tr>
<td>ba6d575a-1344-4516-b777-1404f5593057</td>
<td>AuthenticationContext.ReadWrite.All</td>
<td>Conditional Access Administrator</td>
<td>Allows the app to read and update all authentication context information in your organization on behalf of the signed-in user.</td>
<td>Read and write all authentication context information</td>
</tr>
<tr>
<td>444ed4b6-0554-4dc6-8e9c-3f9a34ee3ff6</td>
<td>BackupRestore-Configuration.Read.All</td>
<td>Microsoft 365 Backup Administrator</td>
<td>Allows the app to read the backup configuration, and list of Microsoft 365 service resources to be backed-up, on behalf of the signed in user.</td>
<td>Read backup configuration policies</td>
</tr>
<tr>
<td>a0244d16-171c-4496-8ffb-7b9b6954d339</td>
<td>BackupRestore-Configuration.ReadWrite.All</td>
<td>Microsoft 365 Backup Administrator</td>
<td>Allows the app to read and update the backup configuration, and list of Microsoft 365 service resources to be backed-up, on behalf of the signed in user.</td>
<td>Read and edit backup configuration policies</td>
</tr>
<tr>
<td>af598c63-4292-4437-b925-e996354d3854</td>
<td>BackupRestore-Control.Read.All</td>
<td>Microsoft 365 Backup Administrator</td>
<td>Allows the app to read the status of M365 backup service (enable/disable), on behalf of the signed in user.</td>
<td>Read the status of the M365 backup service</td>
</tr>
<tr>
<td>96d46335-d92d-41b8-bc9f-273a692381ea</td>
<td>BackupRestore-Control.ReadWrite.All</td>
<td>Microsoft 365 Backup Administrator</td>
<td>Allows the app to update or read the status of M365 backup service (enable/disable), on behalf of the signed in user.</td>
<td>Update or read the status of the M365 backup service</td>
</tr>
<tr>
<td>b4e98de1-4600-4e90-b5e1-7c1dfef04e5c</td>
<td>BackupRestore-Monitor.Read.All</td>
<td>Microsoft 365 Backup Administrator</td>
<td>Allows the app to monitor backup and restore jobs, view quota usage and billing details, on behalf of the signed in user.</td>
<td>Read monitoring, quota and billing information for the tenant</td>
</tr>
<tr>
<td>94b36f78-434f-4904-8c08-421d9a9c1dc2</td>
<td>BackupRestore-Restore.Read.All</td>
<td>Microsoft 365 Backup Administrator</td>
<td>Allows the app to read restore sessions, on behalf of the signed in user.</td>
<td>Read restore sessions</td>
</tr>
<tr>
<td>9f89e109-94b9-4c9b-b4fc-98cdaa54f574</td>
<td>BackupRestore-Restore.ReadWrite.All</td>
<td>Microsoft 365 Backup Administrator</td>
<td>Allows the app to search the backup snapshots for Microsoft 365 resources, and restore Microsoft 365 resources from a backed-up snapshot, on behalf of the signed in user.</td>
<td>Read restore sessions and start restore sessions from backups</td>
</tr>
<tr>
<td>2b24830f-f435-446f-ab5a-b1e70d9a2eb5</td>
<td>BackupRestore-Search.Read.All</td>
<td>Microsoft 365 Backup Administrator</td>
<td>Allows the app to search the backup snapshots for Microsoft 365 resources, on behalf of the signed in user.</td>
<td>Search for metadata properties in backup snapshots</td>
</tr>
<tr>
<td>2bf6d319-dfca-4c22-9879-f88dcfaee6be</td>
<td>BillingConfiguration.ReadWrite.All</td>
<td>Billing Administrator</td>
<td>Allows the app to read and write the billing configuration on all applications on behalf of the signed-in user.</td>
<td>Read and write application billing configuration</td>
</tr>
<tr>
<td>b27a61ec-b99c-4d6a-b126-c4375d08ae30</td>
<td>BitlockerKey.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read BitLocker keys on behalf of the signed-in user, for their owned devices. Allows read of the recovery key.</td>
<td>Read BitLocker keys</td>
</tr>
<tr>
<td>5a107bfc-4f00-4e1a-b67e-66451267bc68</td>
<td>BitlockerKey.ReadBasic.All</td>
<td>Security Reader</td>
<td>Allows the app to read basic BitLocker key properties on behalf of the signed-in user, for their owned devices. Does not allow read of the recovery key itself.</td>
<td>Read BitLocker keys basic information</td>
</tr>
<tr>
<td>d16480b2-e469-4118-846b-d3d177327bee</td>
<td>BusinessScenarioConfig.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read the configurations of your organization&#39;s business scenarios, on behalf of the signed-in user.</td>
<td>Read business scenario configurations</td>
</tr>
<tr>
<td>c47e7b6e-d6f1-4be9-9ffd-1e00f3e32892</td>
<td>BusinessScenarioConfig.Read.OwnedBy</td>
<td>Global Reader</td>
<td>Allows the app to read the configurations of business scenarios it owns, on behalf of the signed-in user.</td>
<td>Read business scenario configurations this app creates or owns</td>
</tr>
<tr>
<td>755e785b-b658-446f-bb22-5a46abd029ea</td>
<td>BusinessScenarioConfig.ReadWrite.All</td>
<td>SharePoint Administrator</td>
<td>Allows the app to read and write the configurations of your organization&#39;s business scenarios, on behalf of the signed-in user.</td>
<td>Read and write business scenario configurations</td>
</tr>
<tr>
<td>b3b7fcff-b4d4-4230-bf6f-90bd91285395</td>
<td>BusinessScenarioConfig.ReadWrite.OwnedBy</td>
<td>User</td>
<td>Allows the app to create new business scenarios and fully manage the configurations of scenarios it owns, on behalf of the signed-in user.</td>
<td>Read and write business scenario configurations this app creates or owns</td>
</tr>
<tr>
<td>25b265c4-5d34-4e44-952d-b567f6d3b96d</td>
<td>BusinessScenarioData.Read.OwnedBy</td>
<td>User</td>
<td>Allows the app to read all data associated with the business scenarios it owns. Data access will be attributed to the signed-in user.</td>
<td>Read all data for business scenarios this app creates or owns</td>
</tr>
<tr>
<td>19932d57-2952-4c60-8634-3655c79fc527</td>
<td>BusinessScenarioData.ReadWrite.OwnedBy</td>
<td>User</td>
<td>Allows the app to fully manage all data associated with the business scenarios it owns. Data access and changes will be attributed to the signed-in user.</td>
<td>Read and write all data for business scenarios this app creates or owns</td>
</tr>
<tr>
<td>305b375b-00fe-48bf-81bc-e8d78954c1b6</td>
<td>CallDelegation.Read</td>
<td>Teams Telephony Administrator</td>
<td>Allows the app to read delegation settings of you</td>
<td>Read delegation settings</td>
</tr>
<tr>
<td>599abf67-f72b-4b5f-98a3-cb38fe646118</td>
<td>CallDelegation.ReadWrite</td>
<td>Teams Telephony Administrator</td>
<td>Allows the app to read and write delegation settings of you</td>
<td>Read and write delegation settings</td>
</tr>
<tr>
<td>43431c03-960e-400f-87c6-8f910321dca3</td>
<td>CallEvents.Read</td>
<td>Compliance Administrator</td>
<td>Allows the app to read call event information for an organization for the signed-in user.</td>
<td>Read call event data</td>
</tr>
<tr>
<td>101147cf-4178-4455-9d58-02b5c164e759</td>
<td>Channel.Create</td>
<td>Teams Administrator</td>
<td>Create channels in any team, on behalf of the signed-in user.</td>
<td>Create channels</td>
</tr>
<tr>
<td>cc83893a-e232-4723-b5af-bd0b01bcfe65</td>
<td>Channel.Delete.All</td>
<td>Teams Administrator</td>
<td>Delete channels in any team, on behalf of the signed-in user.</td>
<td>Delete channels</td>
</tr>
<tr>
<td>2eadaff8-0bce-4198-a6b9-2cfc35a30075</td>
<td>ChannelMember.Read.All</td>
<td>Directory Readers</td>
<td>Read the members of channels, on behalf of the signed-in user.</td>
<td>Read the members of channels</td>
</tr>
<tr>
<td>0c3e411a-ce45-4cd1-8f30-f99a3efa7b11</td>
<td>ChannelMember.ReadWrite.All</td>
<td>Teams Administrator</td>
<td>Add and remove members from channels, on behalf of the signed-in user. Also allows changing a member&#39;s role, for example from owner to non-owner.</td>
<td>Add and remove members from channels</td>
</tr>
<tr>
<td>767156cb-16ae-4d10-8f8b-41b657c8c8c8</td>
<td>ChannelMessage.Read.All</td>
<td>Security Reader</td>
<td>Allows an app to read a channel&#39;s messages in Microsoft Teams, on behalf of the signed-in user.</td>
<td>Read user channel messages</td>
</tr>
<tr>
<td>5922d31f-46c8-4404-9eaf-2117e390a8a4</td>
<td>ChannelMessage.ReadWrite</td>
<td>Teams Administrator</td>
<td>Allows the app to read and write channel messages, on behalf of the signed-in user. This doesn&#39;t allow the app to edit the policyViolation of a channel message.</td>
<td>Read and write user channel messages</td>
</tr>
<tr>
<td>233e0cf1-dd62-48bc-b65b-b38fe87fcf8e</td>
<td>ChannelSettings.Read.All</td>
<td>Teams Communications Support Specialist</td>
<td>Read all channel names, channel descriptions, and channel settings, on behalf of the signed-in user.</td>
<td>Read the names, descriptions, and settings of channels</td>
</tr>
<tr>
<td>d649fb7c-72b4-4eec-b2b4-b15acf79e378</td>
<td>ChannelSettings.ReadWrite.All</td>
<td>Teams Administrator</td>
<td>Read and write the names, descriptions, and settings of all channels, on behalf of the signed-in user.</td>
<td>Read and write the names, descriptions, and settings of channels</td>
</tr>
<tr>
<td>bb64e6fc-6b6d-4752-aea0-dd922dbba588</td>
<td>Chat.ManageDeletion.All</td>
<td>Teams Administrator</td>
<td>Allows the app to delete and recover deleted chats, on behalf of the signed-in user.</td>
<td>Delete and recover deleted chats</td>
</tr>
<tr>
<td>7e9a077b-3711-42b9-b7cb-5fa5f3f7fea7</td>
<td>Chat.ReadWrite.All</td>
<td>Compliance Data Administrator</td>
<td>Allows an app to read and write all one-to-one and group chats in Microsoft Teams, without a signed-in user. Does not allow sending messages.</td>
<td>Read and write all chat messages</td>
</tr>
<tr>
<td>c5a9e2b1-faf6-41d4-8875-d381aa549b24</td>
<td>ChatMember.Read</td>
<td>Compliance Administrator</td>
<td>Read the members of chats, on behalf of the signed-in user.</td>
<td>Read the members of chats</td>
</tr>
<tr>
<td>dea13482-7ea6-488f-8b98-eb5bbecf033d</td>
<td>ChatMember.ReadWrite</td>
<td>Teams Administrator</td>
<td>Add and remove members from chats, on behalf of the signed-in user.</td>
<td>Add and remove members from chats</td>
</tr>
<tr>
<td>9d77138f-f0e2-47ba-ab33-cd246c8b79d1</td>
<td>CloudPC.ReadWrite.All</td>
<td>Windows 365 Administrator</td>
<td>Allows the app to read and write the properties of Cloud PCs on behalf of the signed-in user.</td>
<td>Read and write Cloud PCs</td>
</tr>
<tr>
<td>12ae2e92-14b5-47b2-babb-4e890bbedc0a</td>
<td>Community.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to list Viva Engage communities, and to read their properties on behalf of the signed-in user.</td>
<td>Read all Viva Engage communities</td>
</tr>
<tr>
<td>9e69467d-e0e2-402b-a926-3d796990197f</td>
<td>Community.ReadWrite.All</td>
<td>Yammer Administrator</td>
<td>Allows the app to create Viva Engage communities and read all community properties on behalf of the signed-in user.</td>
<td>Read and write all Viva Engage communities</td>
</tr>
<tr>
<td>c645bb69-adc4-4242-b620-02e635f03bf6</td>
<td>ConfigurationMonitoring.Read.All</td>
<td>Compliance Data Administrator</td>
<td>Allows the app to read all Configuration Monitoring entities on behalf of the signed-in user.</td>
<td>Read all Configuration Monitoring entities</td>
</tr>
<tr>
<td>54505ce9-e719-41f7-a7cc-dbe114e1d811</td>
<td>ConfigurationMonitoring.ReadWrite.All</td>
<td>Compliance Administrator</td>
<td>Allows the app to read and write all Configuration Monitoring entities on behalf of the signed-in user.</td>
<td>Read and write all Configuration Monitoring entities</td>
</tr>
<tr>
<td>f2143d35-9b4b-480d-951c-d083e69eeb2c</td>
<td>ConsentRequest.Create</td>
<td>Cloud Application Administrator</td>
<td>Allows the app to read create consent requests on behalf of the signed-in user.</td>
<td>Create consent requests</td>
</tr>
<tr>
<td>f3bfad56-966e-4590-a536-82ecf548ac1e</td>
<td>ConsentRequest.Read.All</td>
<td>Reports Reader</td>
<td>Allows the app to read consent requests and approvals on behalf of the signed-in user.</td>
<td>Read consent requests</td>
</tr>
<tr>
<td>e694a3a1-7878-46d8-8c29-3d195f6589f4</td>
<td>ConsentRequest.ReadApprove.All</td>
<td>Compliance Administrator</td>
<td>Allows the app to read and approve consent requests on behalf of the signed in user.</td>
<td>Read and approve consent requests</td>
</tr>
<tr>
<td>497d9dfa-3bd1-481a-baab-90895e54568c</td>
<td>ConsentRequest.ReadWrite.All</td>
<td>Compliance Administrator</td>
<td>Allows the app to read app consent requests and approvals, and deny or approve those requests on behalf of the signed-in user.</td>
<td>Read and write consent requests</td>
</tr>
<tr>
<td>aeb2982d-632d-4155-b533-18756ab6fdd8</td>
<td>CopilotSettings-LimitedMode.Read</td>
<td>AI Administrator</td>
<td>Allows the app to read organization-wide copilot limited mode setting on behalf of the signed-in user.</td>
<td>Read organization-wide copilot limited mode setting</td>
</tr>
<tr>
<td>4704e5b2-0ada-4aa0-b18c-00ad7525bc06</td>
<td>CopilotSettings-LimitedMode.ReadWrite</td>
<td>AI Administrator</td>
<td>Allows the app to read and write organization-wide copilot limited mode setting on behalf of the signed-in user.</td>
<td>Read and write organization-wide copilot limited mode setting</td>
</tr>
<tr>
<td>81594d25-e88e-49cf-ac8c-fecbff49f994</td>
<td>CrossTenantInformation.ReadBasic.All</td>
<td>Directory Readers</td>
<td>Allows the application to obtain basic tenant information about another target tenant within the Azure AD ecosystem on behalf of the signed-in user.</td>
<td>Read cross-tenant basic information</td>
</tr>
<tr>
<td>cb1ba48f-d22b-4325-a07f-74135a62ee41</td>
<td>CrossTenantUserProfileSharing.Read</td>
<td>Compliance Administrator</td>
<td>Allows the application to list and query user profile information associated with the current tenant on behalf of the signed-in user.�� It also permits the application to export external user data (e.g. customer content or system-generated logs), associated with the current tenant on behalf of the signed-in user.</td>
<td>Read shared cross-tenant user profile and export data</td>
</tr>
<tr>
<td>759dcd16-3c90-463c-937e-abf89f991c18</td>
<td>CrossTenantUserProfileSharing.Read.All</td>
<td>Compliance Administrator</td>
<td>Allows the application to list and query any shared user profile information associated with the current tenant on behalf of the signed-in user.�� It also permits the application to export external user data (e.g. customer content or system-generated logs), for any user associated with the current tenant on behalf of the signed-in user.</td>
<td>Read all shared cross-tenant user profiles and export their data</td>
</tr>
<tr>
<td>eed0129d-dc60-4f30-8641-daf337a39ffd</td>
<td>CrossTenantUserProfileSharing.ReadWrite</td>
<td>Identity Governance Administrator</td>
<td>Allows the application to list and query user profile information associated with the current tenant on behalf of the signed-in user.�� It also permits the application to export and remove external user data (e.g. customer content or system-generated logs), associated with the current tenant on behalf of the signed-in user.</td>
<td>Read shared cross-tenant user profile and export or delete data</td>
</tr>
<tr>
<td>64dfa325-cbf8-48e3-938d-51224a0cac01</td>
<td>CrossTenantUserProfileSharing.ReadWrite.All</td>
<td>Compliance Administrator</td>
<td>Allows the application to list and query any shared user profile information associated with the current tenant on behalf of the signed-in user.�� It also permits the application to export and remove external user data (e.g. customer content or system-generated logs), for any user associated with the current tenant on behalf of the signed-in user.</td>
<td>Read all shared cross-tenant user profiles and export or delete their data</td>
</tr>
<tr>
<td>b2052569-c98c-4f36-a5fb-43e5c111e6d0</td>
<td>CustomAuthenticationExtension.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read your organization&#39;s custom authentication extensions on behalf of the signed-in user.</td>
<td>Read your organization&#39;s custom authentication extensions</td>
</tr>
<tr>
<td>8dfcf82f-15d0-43b3-bc78-a958a13a5792</td>
<td>CustomAuthenticationExtension.ReadWrite.All</td>
<td>Authentication Extensibility Administrator</td>
<td>Allows the app to read or write your organization&#39;s custom authentication extensions on behalf of the signed-in user.</td>
<td>Read and write your organization&#39;s custom authentication extensions</td>
</tr>
<tr>
<td>b13ff42e-f321-4d7d-a462-141c46a1b832</td>
<td>CustomDetection.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read custom detection rules on behalf of the signed-in user.</td>
<td>Read custom detection rules</td>
</tr>
<tr>
<td>c34088fb-0649-4714-af0b-bcbfec155897</td>
<td>CustomDetection.ReadWrite.All</td>
<td>Compliance Administrator</td>
<td>Allows the app to read and write custom detection rules on behalf of the signed-in user.</td>
<td>Read and write custom detection rules</td>
</tr>
<tr>
<td>b46ffa80-fe3d-4822-9a1a-c200932d54d0</td>
<td>CustomSecAttributeAssignment.Read.All</td>
<td>Attribute Assignment Reader</td>
<td>Allows the app to read custom security attribute assignments for all principals in the tenant on behalf of a signed in user.</td>
<td>Read custom security attribute assignments</td>
</tr>
<tr>
<td>ca46335e-8453-47cd-a001-8459884efeae</td>
<td>CustomSecAttributeAssignment.ReadWrite.All</td>
<td>Attribute Assignment Administrator</td>
<td>Allows the app to read and write custom security attribute assignments for all principals in the tenant on behalf of a signed in user.</td>
<td>Read and write custom security attribute assignments</td>
</tr>
<tr>
<td>1fcdeaab-b519-44dd-bffc-ed1fd15a24e0</td>
<td>CustomSecAttributeAuditLogs.Read.All</td>
<td>Attribute Log Reader</td>
<td>Allows the app to read audit logs for events that contain information about custom security attributes, on behalf of the signed-in user.</td>
<td>Read custom security attribute audit logs</td>
</tr>
<tr>
<td>ce026878-a0ff-4745-a728-d4fedd086c07</td>
<td>CustomSecAttributeDefinition.Read.All</td>
<td>Attribute Definition Reader</td>
<td>Allows the app to read custom security attribute definitions for the tenant on behalf of a signed in user.</td>
<td>Read custom security attribute definitions</td>
</tr>
<tr>
<td>8b0160d4-5743-482b-bb27-efc0a485ca4a</td>
<td>CustomSecAttributeDefinition.ReadWrite.All</td>
<td>Attribute Definition Administrator</td>
<td>Allows the app to read and write custom security attribute definitions for the tenant on behalf of a signed in user.</td>
<td>Read and write custom security attribute definitions</td>
</tr>
<tr>
<td>9ddd870d-077c-49e7-b3e3-6b3012a8a880</td>
<td>CustomSecAttributeProvisioning.Read.All</td>
<td>Attribute Provisioning Reader</td>
<td>Allows the app to read the provisioning configuration of all active custom security attributes on behalf of a signed in user.</td>
<td>Read the provisioning configuration of all active custom security attributes</td>
</tr>
<tr>
<td>1140d9e4-6776-433e-a9e4-b9831adbb2e0</td>
<td>CustomSecAttributeProvisioning.ReadWrite.All</td>
<td>Attribute Provisioning Administrator</td>
<td>Allows the app to read and edit the provisioning configuration of all active custom security attributes on behalf of a signed in user.</td>
<td>Read and edit the provisioning configuration of all active custom security attributes</td>
</tr>
<tr>
<td>de6ea87d-10bd-467c-8682-d525a0c61b89</td>
<td>CustomTags.Read.All</td>
<td>Compliance Administrator</td>
<td>Read custom tags data on behalf of the signed-in user</td>
<td>Read all custom tags data</td>
</tr>
<tr>
<td>2f1bbe0a-f34b-4efb-9edb-8db8dcb50eca</td>
<td>CustomTags.ReadWrite.All</td>
<td>Compliance Data Administrator</td>
<td>Read and write custom tags data on behalf of the signed-in user</td>
<td>Read and write custom tags data</td>
</tr>
<tr>
<td>0c0064ea-477b-4130-82a5-4c2cc4ff68aa</td>
<td>DelegatedAdminRelationship.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read details of delegated admin relationships with customers like access details (that includes roles) and the duration as well as specific role assignments to security groups on behalf of the signed-in user.</td>
<td>Read Delegated Admin relationships with customers</td>
</tr>
<tr>
<td>885f682f-a990-4bad-a642-36736a74b0c7</td>
<td>DelegatedAdminRelationship.ReadWrite.All</td>
<td>Partner Tier2 Support</td>
<td>Allows the app to manage (create-update-terminate) Delegated Admin relationships with customers as well as role assignments to security groups for active Delegated Admin relationships on behalf of the signed-in user.</td>
<td>Manage Delegated Admin relationships with customers</td>
</tr>
<tr>
<td>a197cdc4-a8e8-4d49-9d35-4ca7c83887b4</td>
<td>DelegatedPermissionGrant.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read delegated permission grants, on behalf of the signed in user.</td>
<td>Read delegated permission grants</td>
</tr>
<tr>
<td>41ce6ca6-6826-4807-84f1-1c82854f7ee5</td>
<td>DelegatedPermissionGrant.ReadWrite.All</td>
<td>Conditional Access Administrator</td>
<td>Allows the app to manage permission grants for delegated permissions exposed by any API (including Microsoft Graph), on behalf of the signed in user.</td>
<td>Manage all delegated permission grants</td>
</tr>
<tr>
<td>edc92e89-a987-48a9-911a-a7b1967dd7b1</td>
<td>Device.CreateFromOwnedTemplate</td>
<td>Windows 365 Administrator</td>
<td>Allows the app to create device objects based on device templates owned by the signed-in user, on behalf of the signed in user.</td>
<td>Create devices based on owned device templates</td>
</tr>
<tr>
<td>951183d1-1a61-466f-a6d1-1fde911bfd95</td>
<td>Device.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read your organization&#39;s devices&#39; configuration information on behalf of the signed-in user.</td>
<td>Read all devices</td>
</tr>
<tr>
<td>280b3b69-0437-44b1-bc20-3b2fca1ee3e9</td>
<td>DeviceLocalCredential.Read.All</td>
<td>Helpdesk Administrator</td>
<td>Allows the app to read device local credential properties including passwords, on behalf of the signed-in user.</td>
<td>Read device local credential passwords</td>
</tr>
<tr>
<td>9917900e-410b-4d15-846e-42a357488545</td>
<td>DeviceLocalCredential.ReadBasic.All</td>
<td>Directory Readers</td>
<td>Allows the app to read device local credential properties excluding passwords, on behalf of the signed-in user.</td>
<td>Read device local credential properties</td>
</tr>
<tr>
<td>4edf5f54-4666-44af-9de9-0144fb4b6e8c</td>
<td>DeviceManagementApps.Read.All</td>
<td>Intune Administrator</td>
<td>Allows the app to read the properties, group assignments and status of apps, app configurations and app protection policies managed by Microsoft Intune.</td>
<td>Read Microsoft Intune apps</td>
</tr>
<tr>
<td>7b3f05d5-f68c-4b8d-8c59-a2ecd12f24af</td>
<td>DeviceManagementApps.ReadWrite.All</td>
<td>Intune Administrator</td>
<td>Allows the app to read and write the properties, group assignments and status of apps, app configurations and app protection policies managed by Microsoft Intune.</td>
<td>Read and write Microsoft Intune apps</td>
</tr>
<tr>
<td>ac5c8443-d999-471f-9247-ce92cf5c5560</td>
<td>DeviceManagementCloudCA.Read.All</td>
<td>Compliance Administrator</td>
<td>Allows the app to read certification authority information on behalf of the signed-in user.</td>
<td>Read Microsoft Cloud PKI objects</td>
</tr>
<tr>
<td>93028c58-65aa-48db-a706-1fe4ada325ec</td>
<td>DeviceManagementCloudCA.ReadWrite.All</td>
<td>Compliance Administrator</td>
<td>Allows the app to read and write certification authority information on behalf of the signed-in user.</td>
<td>Read and write Microsoft Cloud PKI objects</td>
</tr>
<tr>
<td>f1493658-876a-4c87-8fa7-edb559b3476a</td>
<td>DeviceManagementConfiguration.Read.All</td>
<td>Intune Administrator</td>
<td>Allows the app to read properties of Microsoft Intune-managed device configuration and device compliance policies and their assignment to groups.</td>
<td>Read Microsoft Intune Device Configuration and Policies</td>
</tr>
<tr>
<td>0883f392-0a7a-443d-8c76-16a6d39c7b63</td>
<td>DeviceManagementConfiguration.ReadWrite.All</td>
<td>Intune Administrator</td>
<td>Allows the app to read and write properties of Microsoft Intune-managed device configuration and device compliance policies and their assignment to groups.</td>
<td>Read and write Microsoft Intune Device Configuration and Policies</td>
</tr>
<tr>
<td>3404d2bf-2b13-457e-a330-c24615765193</td>
<td>DeviceManagementManagedDevices.PrivilegedOperations.All</td>
<td>Intune Administrator</td>
<td>Allows the app to perform remote high impact actions such as wiping the device or resetting the passcode on devices managed by Microsoft Intune.</td>
<td>Perform user-impacting remote actions on Microsoft Intune devices</td>
</tr>
<tr>
<td>314874da-47d6-4978-88dc-cf0d37f0bb82</td>
<td>DeviceManagementManagedDevices.Read.All</td>
<td>Compliance Administrator</td>
<td>Allows the app to read the properties of devices managed by Microsoft Intune.</td>
<td>Read Microsoft Intune devices</td>
</tr>
<tr>
<td>44642bfe-8385-4adc-8fc6-fe3cb2c375c3</td>
<td>DeviceManagementManagedDevices.ReadWrite.All</td>
<td>Intune Administrator</td>
<td>Allows the app to read and write the properties of devices managed by Microsoft Intune. Does not allow high impact operations such as remote wipe and password reset on the device�??s owner.</td>
<td>Read and write Microsoft Intune devices</td>
</tr>
<tr>
<td>49f0cc30-024c-4dfd-ab3e-82e137ee5431</td>
<td>DeviceManagementRBAC.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read the properties relating to the Microsoft Intune Role-Based Access Control (RBAC) settings.</td>
<td>Read Microsoft Intune RBAC settings</td>
</tr>
<tr>
<td>0c5e8a55-87a6-4556-93ab-adc52c4d862d</td>
<td>DeviceManagementRBAC.ReadWrite.All</td>
<td>Intune Administrator</td>
<td>Allows the app to read and write the properties relating to the Microsoft Intune Role-Based Access Control (RBAC) settings.</td>
<td>Read and write Microsoft Intune RBAC settings</td>
</tr>
<tr>
<td>d32381d8-ee89-4220-9c83-b672aa68d404</td>
<td>DeviceManagementScripts.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read Microsoft Intune device compliance scripts, device management scripts, device shell scripts, device custom attribute shell scripts and device health scripts on behalf of the signed in user.</td>
<td>Read Microsoft Intune Scripts</td>
</tr>
<tr>
<td>8b9d79d0-ad75-4566-8619-f7500ecfcebe</td>
<td>DeviceManagementScripts.ReadWrite.All</td>
<td>Intune Administrator</td>
<td>Allows the app to read and write Microsoft Intune device compliance scripts, device management scripts, device shell scripts, device custom attribute shell scripts and device health scripts on behalf of the signed in user.</td>
<td>Read and write Microsoft Intune Scripts</td>
</tr>
<tr>
<td>8696daa5-bce5-4b2e-83f9-51b6defc4e1e</td>
<td>DeviceManagementServiceConfig.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read Microsoft Intune service properties including device enrollment and third party service connection configuration.</td>
<td>Read Microsoft Intune configuration</td>
</tr>
<tr>
<td>662ed50a-ac44-4eef-ad86-62eed9be2a29</td>
<td>DeviceManagementServiceConfig.ReadWrite.All</td>
<td>Intune Administrator</td>
<td>Allows the app to read and write Microsoft Intune service properties including device enrollment and third party service connection configuration.</td>
<td>Read and write Microsoft Intune configuration</td>
</tr>
<tr>
<td>0b1717ff-3e42-4a73-8c29-e6b2e1093960</td>
<td>DeviceTemplate.Create</td>
<td>Cloud Device Administrator</td>
<td>Allows the app to create device templates on behalf of the signed in user. The user is marked as owners of the created device template. As a member of owners, the user will be allowed to manage devices created from the template.</td>
<td>Create device templates</td>
</tr>
<tr>
<td>2bcae0b0-aa93-48e4-a9e4-855482dffdcd</td>
<td>DeviceTemplate.Read.All</td>
<td>Cloud Device Administrator</td>
<td>Allows the app to read all device templates, on behalf of the signed in user.</td>
<td>Read all device templates</td>
</tr>
<tr>
<td>2d372e98-f1ae-406c-a157-2ea83f6f5e4a</td>
<td>DeviceTemplate.ReadWrite.All</td>
<td>Cloud Device Administrator</td>
<td>Allows the app to create, read, update and delete the device template, on behalf of the signed in user. It also allows the app to add or remove owners on any device template.</td>
<td>Read and write all device templates</td>
</tr>
<tr>
<td>0e263e50-5827-48a4-b97c-d940288653c7</td>
<td>Directory.AccessAsUser.All</td>
<td>Global Administrator</td>
<td>Allows the app to have the same access to information in the directory as the signed-in user.</td>
<td>Access directory as the signed in user</td>
</tr>
<tr>
<td>06da0dbc-49e2-44d2-8312-53f166ab848a</td>
<td>Directory.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read data in your organization&#39;s directory, such as users, groups and apps.</td>
<td>Read directory data</td>
</tr>
<tr>
<td>c5366453-9fb0-48a5-a156-24f0c49a4b84</td>
<td>Directory.ReadWrite.All</td>
<td>Directory Writers</td>
<td>Allows the app to read and write data in your organization&#39;s directory, such as users, and groups.  It does not allow the app to delete users or groups, or reset user passwords.</td>
<td>Read and write directory data</td>
</tr>
<tr>
<td>34d3bd24-f6a6-468c-b67c-0c365c1d6410</td>
<td>DirectoryRecommendations.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read Azure AD recommendations, on behalf of the signed-in user.</td>
<td>Read Azure AD recommendations</td>
</tr>
<tr>
<td>f37235e8-90a0-4189-93e2-e55b53867ccd</td>
<td>DirectoryRecommendations.ReadWrite.All</td>
<td>Conditional Access Administrator</td>
<td>Allows the app to read and update Azure AD recommendations, on behalf of the signed-in user.</td>
<td>Read and update Azure AD recommendations</td>
</tr>
<tr>
<td>2f9ee017-59c1-4f1d-9472-bd5529a7b311</td>
<td>Domain.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read all domain properties on behalf of the signed-in user.</td>
<td>Read domains.</td>
</tr>
<tr>
<td>0b5d694c-a244-4bde-86e6-eb5cd07730fe</td>
<td>Domain.ReadWrite.All</td>
<td>Domain Name Administrator</td>
<td>Allows the app to read and write all domain properties on behalf of the signed-in user. Also allows the app to add, verify and remove domains.</td>
<td>Read and write domains</td>
</tr>
<tr>
<td>99201db3-7652-4d5a-809a-bdb94f85fe3c</td>
<td>eDiscovery.Read.All</td>
<td>Compliance Administrator</td>
<td>Allows the app to read eDiscovery objects such as cases, custodians, review sets and other related objects on behalf of the signed-in user.</td>
<td>Read all eDiscovery objects</td>
</tr>
<tr>
<td>acb8f680-0834-4146-b69e-4ab1b39745ad</td>
<td>eDiscovery.ReadWrite.All</td>
<td>Compliance Administrator</td>
<td>Allows the app to read and write eDiscovery objects such as cases, custodians, review sets and other related objects on behalf of the signed-in user.</td>
<td>Read and write all eDiscovery objects</td>
</tr>
<tr>
<td>8523895c-6081-45bf-8a5d-f062a2f12c9f</td>
<td>EduAdministration.Read</td>
<td>Global Reader</td>
<td>Read the state and settings of all Microsoft education apps on behalf of the user.</td>
<td>Read education app settings</td>
</tr>
<tr>
<td>63589852-04e3-46b4-bae9-15d5b1050748</td>
<td>EduAdministration.ReadWrite</td>
<td>Intune Administrator</td>
<td>Manage the state and settings of all Microsoft education apps on behalf of the user.</td>
<td>Manage education app settings</td>
</tr>
<tr>
<td>091460c9-9c4a-49b2-81ef-1f3d852acce2</td>
<td>EduAssignments.Read</td>
<td>Directory Readers</td>
<td>Allows the app to read assignments and their grades on behalf of the user.</td>
<td>Read users&#39; class assignments and their grades</td>
</tr>
<tr>
<td>c0b0103b-c053-4b2e-9973-9f3a544ec9b8</td>
<td>EduAssignments.ReadBasic</td>
<td>Directory Readers</td>
<td>Allows the app to read assignments without grades on behalf of the user.</td>
<td>Read users&#39; class assignments without grades</td>
</tr>
<tr>
<td>2f233e90-164b-4501-8bce-31af2559a2d3</td>
<td>EduAssignments.ReadWrite</td>
<td>Teams Administrator</td>
<td>Allows the app to read and write assignments and their grades on behalf of the user.</td>
<td>Read and write users&#39; class assignments and their grades</td>
</tr>
<tr>
<td>2ef770a1-622a-47c4-93ee-28d6adbed3a0</td>
<td>EduAssignments.ReadWriteBasic</td>
<td>Intune Administrator</td>
<td>Allows the app to read and write assignments without grades on behalf of the user.</td>
<td>Read and write users&#39; class assignments without grades</td>
</tr>
<tr>
<td>484859e8-b9e2-4e92-b910-84db35dadd29</td>
<td>EduCurricula.Read</td>
<td>Global Reader</td>
<td>Allows the app to read the user&#39;s modules and resources on behalf of the signed-in user.</td>
<td>Read the user&#39;s class modules and resources</td>
</tr>
<tr>
<td>4793c53b-df34-44fd-8d26-d15c517732f5</td>
<td>EduCurricula.ReadWrite</td>
<td>Compliance Administrator</td>
<td>Allows the app to read and write user&#39;s modules and resources on behalf of the signed-in user.</td>
<td>Read and write the user&#39;s class modules and resources</td>
</tr>
<tr>
<td>a4389601-22d9-4096-ac18-36a927199112</td>
<td>EduRoster.Read</td>
<td>Directory Readers</td>
<td>Allows the app to read the structure of schools and classes in an organization&#39;s roster and education-specific information about users to be read on behalf of the user.</td>
<td>Read users&#39; view of the roster</td>
</tr>
<tr>
<td>5d186531-d1bf-4f07-8cea-7c42119e1bd9</td>
<td>EduRoster.ReadBasic</td>
<td>Directory Readers</td>
<td>Allows the app to read a limited subset of the properties from the structure of schools and classes in an organization&#39;s roster and a limited subset of properties about users to be read on behalf of the user.��Includes name, status, education role, email address and photo.</td>
<td>Read a limited subset of users&#39; view of the roster</td>
</tr>
<tr>
<td>359e19a6-e3fa-4d7f-bcab-d28ec592b51e</td>
<td>EduRoster.ReadWrite</td>
<td>User Administrator</td>
<td>Allows the app to read and write the structure of schools and classes in an organization&#39;s roster and education-specific information about users to be read and written on behalf of the user.</td>
<td>Read and write users&#39; view of the roster</td>
</tr>
<tr>
<td>3cad91a5-8413-4c4a-acfe-dfeb83d1366d</td>
<td>EngagementRole.Read.All</td>
<td>Yammer Administrator</td>
<td>Allows the app to list all Viva Engage roles and role memberships on behalf of the signed-in user.</td>
<td>Read all Viva Engage roles and role memberships</td>
</tr>
<tr>
<td>4905982d-6459-4ccd-949c-949fefc0a8f2</td>
<td>EngagementRole.ReadWrite.All</td>
<td>Yammer Administrator</td>
<td>Allows the app to assign Viva Engage role to a user, and remove a Viva Engage role from a user behalf of the signed-in user.</td>
<td>Modify Viva Engage role membership</td>
</tr>
<tr>
<td>5449aa12-1393-4ea2-a7c7-d0e06c1a56b2</td>
<td>EntitlementManagement.Read.All</td>
<td>Identity Governance Administrator</td>
<td>Allows the app to read access packages and related entitlement management resources on behalf of the signed-in user.</td>
<td>Read all entitlement management resources</td>
</tr>
<tr>
<td>ae7a573d-81d7-432b-ad44-4ed5c9d89038</td>
<td>EntitlementManagement.ReadWrite.All</td>
<td>Identity Governance Administrator</td>
<td>Allows the app to request access to and management of access packages and related entitlement management resources on behalf of the signed-in user.</td>
<td>Read and write entitlement management resources</td>
</tr>
<tr>
<td>f7dd3bed-5eec-48da-bc73-1c0ef50bc9a1</td>
<td>EventListener.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read your organization&#39;s authentication event listeners on behalf of the signed-in user.</td>
<td>Read your organization&#39;s authentication event listeners</td>
</tr>
<tr>
<td>d11625a6-fe21-4fc6-8d3d-063eba5525ad</td>
<td>EventListener.ReadWrite.All</td>
<td>Global Reader</td>
<td>Allows the app to read or write your organization&#39;s authentication event listeners on behalf of the signed-in user.</td>
<td>Read and write your organization&#39;s authentication event listeners</td>
</tr>
<tr>
<td>a38267a5-26b6-4d76-9493-935b7599116b</td>
<td>ExternalConnection.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read all external connections on behalf of a signed-in user. The signed-in user must be an administrator.</td>
<td>Read all external connections</td>
</tr>
<tr>
<td>bbbbd9b3-3566-4931-ac37-2b2180d9e334</td>
<td>ExternalConnection.ReadWrite.All</td>
<td>Global Administrator</td>
<td>Allows the app to read and write all external connections on behalf of a signed-in user. The signed-in user must be an administrator.</td>
<td>Read and write all external connections</td>
</tr>
<tr>
<td>4082ad95-c812-4f02-be92-780c4c4f1830</td>
<td>ExternalConnection.ReadWrite.OwnedBy</td>
<td>Global Reader</td>
<td>Allows the app to read and write settings of external connections on behalf of a signed-in user. The signed-in user must be an administrator. The app can only read and write settings of connections that it is authorized to.</td>
<td>Read and write external connections</td>
</tr>
<tr>
<td>922f9392-b1b7-483c-a4be-0089be7704fb</td>
<td>ExternalItem.Read.All</td>
<td>Directory Readers</td>
<td>Allow the app to read external datasets and content, on behalf of the signed-in user.</td>
<td>Read items in external datasets</td>
</tr>
<tr>
<td>b02c54f8-eb48-4c50-a9f0-a149e5a2012f</td>
<td>ExternalItem.ReadWrite.All</td>
<td>Global Administrator</td>
<td>Allows the app to read and write all external items on behalf of a signed-in user. The signed-in user must be an administrator.</td>
<td>Read and write all external items</td>
</tr>
<tr>
<td>4367b9d7-cee7-4995-853c-a0bdfe95c1f9</td>
<td>ExternalItem.ReadWrite.OwnedBy</td>
<td>Global Administrator</td>
<td>Allows the app to read and write external items on behalf of a signed-in user. The signed-in user must be an administrator. The app can only read external items of the connection that it is authorized to.</td>
<td>Read and write external items</td>
</tr>
<tr>
<td>47167bec-55a7-4caf-9ecc-8d4566e3cfb1</td>
<td>ExternalUserProfile.Read.All</td>
<td>External ID User Flow Attribute Administrator</td>
<td>Allows the app to read available properties of external user profiles, on behalf of the signed-in user.</td>
<td>Read external user profiles</td>
</tr>
<tr>
<td>c6068dc7-a791-46a4-a811-b8228e6649ab</td>
<td>ExternalUserProfile.ReadWrite.All</td>
<td>User Administrator</td>
<td>Allows the app to read and write available properties of external user profiles, on behalf of the signed-in user.</td>
<td>Read and write external user profiles</td>
</tr>
<tr>
<td>ef2779dc-ef1b-4211-8310-8a0ac2450081</td>
<td>Files.SelectedOperations.Selected</td>
<td>User</td>
<td>Allow the application to access files explicitly permissioned to the application on behalf of the signed in user.  The specific files and the permissions granted will be configured in SharePoint Online or OneDrive.</td>
<td>Access selected Files, on behalf of the signed-in user</td>
</tr>
<tr>
<td>527b6d64-cdf5-4b8b-b336-4aa0b8ca2ce5</td>
<td>FileStorageContainer.Manage.All</td>
<td>Global Administrator</td>
<td>Allows the application to utilize the file storage container administration capabilities on behalf of an administrator user.</td>
<td>Manage all file storage containers</td>
</tr>
<tr>
<td>085ca537-6565-41c2-aca7-db852babc212</td>
<td>FileStorageContainer.Selected</td>
<td>User</td>
<td>Allows the application to utilize the file storage container platform to manage containers on behalf of the signed in user. The specific file storage containers and the permissions granted to them will be configured in Microsoft 365 by the developer of each container type.</td>
<td>Access selected file storage containers</td>
</tr>
<tr>
<td>092211d9-ca1a-427b-813e-b79c7653fe71</td>
<td>Goals-Export.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read all goals and export jobs that the signed-in user can access.</td>
<td>Read all goals and export jobs that a user can access</td>
</tr>
<tr>
<td>2edeb9fd-4228-480c-a26d-2ed52011cf3d</td>
<td>Goals-Export.ReadWrite.All</td>
<td>Viva Goals Administrator</td>
<td>Allows the app to read goals, create and read export jobs that the signed-in user can access.</td>
<td>Have full access to all goals and export jobs a user can access</td>
</tr>
<tr>
<td>c92fbbc2-50e0-4842-93ef-385c3293ea3d</td>
<td>Group-Conversation.Read.All</td>
<td>Groups Administrator</td>
<td>Allows the app to read group conversations that the signed-in user has access to.</td>
<td>Read group conversations</td>
</tr>
<tr>
<td>302bcbb5-855a-4e49-ae20-94a331b0281e</td>
<td>Group-Conversation.ReadWrite.All</td>
<td>Groups Administrator</td>
<td>Allows the app to read and write group conversations that the signed-in user has access to.</td>
<td>Read and write group conversations</td>
</tr>
<tr>
<td>5f8c59db-677d-491f-a6b8-5f174b11ec1d</td>
<td>Group.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to list groups, and to read their properties and all group memberships on behalf of the signed-in user.  Also allows the app to read calendar, conversations, files, and other group content for all groups the signed-in user can access.</td>
<td>Read all groups</td>
</tr>
<tr>
<td>4e46008b-f24c-477d-8fff-7bb4ec7aafe0</td>
<td>Group.ReadWrite.All</td>
<td>Groups Administrator</td>
<td>Allows the app to create groups and read all group properties and memberships on behalf of the signed-in user.  Additionally allows group owners to manage their groups and allows group members to update group content.</td>
<td>Read and write all groups</td>
</tr>
<tr>
<td>bc024368-1153-4739-b217-4326f2e966d0</td>
<td>GroupMember.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to list groups, read basic group properties and read membership of all groups the signed-in user has access to.</td>
<td>Read group memberships</td>
</tr>
<tr>
<td>f81125ac-d3b7-4573-a3b2-7099cc39df9e</td>
<td>GroupMember.ReadWrite.All</td>
<td>Groups Administrator</td>
<td>Allows the app to list groups, read basic properties, read and update the membership of the groups the signed-in user has access to. Group properties and owners cannot be updated and groups cannot be deleted.</td>
<td>Read and write group memberships</td>
</tr>
<tr>
<td>74b4ff32-4917-4536-a66d-38a4861e6220</td>
<td>HealthMonitoringAlert.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read all scenario health monitoring alerts</td>
<td>Read all scenario health monitoring alerts</td>
</tr>
<tr>
<td>b7c60f27-2195-4d5f-96a7-6b98bdfd9664</td>
<td>HealthMonitoringAlert.ReadWrite.All</td>
<td>Global Reader</td>
<td>Allows the app to read and write all scenario monitoring alerts, on behalf of the signed-in user.</td>
<td>Read and write all scenario monitoring alerts</td>
</tr>
<tr>
<td>fb873030-8626-47e6-96ff-8a5bff3b725f</td>
<td>HealthMonitoringAlertConfig.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read all scenario health monitoring alert configurations</td>
<td>Read all scenario health monitoring alert configurations</td>
</tr>
<tr>
<td>b3e5ebc6-1c23-4337-8286-3f27165addb4</td>
<td>HealthMonitoringAlertConfig.ReadWrite.All</td>
<td>Global Administrator</td>
<td>Allows the app to read and write all scenario monitoring alert configurations, on behalf of the signed-in user.</td>
<td>Read and write all scenario monitoring alert configurations.</td>
</tr>
<tr>
<td>43781733-b5a7-4d1b-98f4-e8edff23e1a9</td>
<td>IdentityProvider.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read your organization�??s identity (authentication) providers�?? properties on behalf of the user.</td>
<td>Read identity providers</td>
</tr>
<tr>
<td>f13ce604-1677-429f-90bd-8a10b9f01325</td>
<td>IdentityProvider.ReadWrite.All</td>
<td>External Identity Provider Administrator</td>
<td>Allows the app to read and write your organization�??s identity (authentication) providers�?? properties on behalf of the user.</td>
<td>Read and write identity providers</td>
</tr>
<tr>
<td>8f6a01e7-0391-4ee5-aa22-a3af122cef27</td>
<td>IdentityRiskEvent.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read identity risk event information for all users in your organization on behalf of the signed-in user.</td>
<td>Read identity risk event information</td>
</tr>
<tr>
<td>9e4862a5-b68f-479e-848a-4e07e25c9916</td>
<td>IdentityRiskEvent.ReadWrite.All</td>
<td>Security Operator</td>
<td>Allows the app to read and update identity risk event information for all users in your organization on behalf of the signed-in user.��Update operations include confirming risk event detections.��</td>
<td>Read and write risk event information</td>
</tr>
<tr>
<td>ea5c4ab0-5a73-4f35-8272-5d5337884e5d</td>
<td>IdentityRiskyServicePrincipal.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read all identity risky service principal information for your organization, on behalf of the signed-in user.</td>
<td>Read all identity risky service principal information</td>
</tr>
<tr>
<td>bb6f654c-d7fd-4ae3-85c3-fc380934f515</td>
<td>IdentityRiskyServicePrincipal.ReadWrite.All</td>
<td>Security Reader</td>
<td>Allows the app to read and update identity risky service principal information for all service principals in your organization, on behalf of the signed-in user. Update operations include dismissing risky service principals.</td>
<td>Read and write all identity risky service principal information</td>
</tr>
<tr>
<td>d04bb851-cb7c-4146-97c7-ca3e71baf56c</td>
<td>IdentityRiskyUser.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read identity risky user information for all users in your organization on behalf of the signed-in user.</td>
<td>Read identity risky user information</td>
</tr>
<tr>
<td>e0a7cdbb-08b0-4697-8264-0069786e9674</td>
<td>IdentityRiskyUser.ReadWrite.All</td>
<td>Security Operator</td>
<td>Allows the app to read and update identity risky user information for all users in your organization on behalf of the signed-in user.��Update operations include dismissing risky users.</td>
<td>Read and write risky user information</td>
</tr>
<tr>
<td>2903d63d-4611-4d43-99ce-a33f3f52e343</td>
<td>IdentityUserFlow.Read.All</td>
<td>External ID User Flow Administrator</td>
<td>Allows the app to read your organization&#39;s user flows, on behalf of the signed-in user.</td>
<td>Read all identity user flows</td>
</tr>
<tr>
<td>281892cc-4dbf-4e3a-b6cc-b21029bb4e82</td>
<td>IdentityUserFlow.ReadWrite.All</td>
<td>External ID User Flow Administrator</td>
<td>Allows the app to read or write your organization&#39;s user flows, on behalf of the signed-in user.</td>
<td>Read and write all identity user flows</td>
</tr>
<tr>
<td>d19c0de5-7ecb-4aba-b090-da35ebcd5425</td>
<td>IndustryData-DataConnector.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read data connectors on behalf of the signed-in user.</td>
<td>View data connector definitions</td>
</tr>
<tr>
<td>5ce933ac-3997-4280-aed0-cc072e5c062a</td>
<td>IndustryData-DataConnector.ReadWrite.All</td>
<td>Global Administrator</td>
<td>Allows the app to read and write data connectors on behalf of the signed-in user.</td>
<td>Manage data connector definitions</td>
</tr>
<tr>
<td>fc47391d-ab2c-410f-9059-5600f7af660d</td>
<td>IndustryData-DataConnector.Upload</td>
<td>Service Support Administrator</td>
<td>Allows the app to upload data files to a data connector on behalf of the signed-in user.</td>
<td>Upload files to a data connector</td>
</tr>
<tr>
<td>cb0774da-a605-42af-959c-32f438fb38f4</td>
<td>IndustryData-InboundFlow.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read inbound data flows on behalf of the signed-in user.</td>
<td>View inbound flow definitions</td>
</tr>
<tr>
<td>97044676-2cec-40ee-bd70-38df444c9e70</td>
<td>IndustryData-InboundFlow.ReadWrite.All</td>
<td>Global Administrator</td>
<td>Allows the app to read and write inbound data flows on behalf of the signed-in user.</td>
<td>Manage inbound flow definitions</td>
</tr>
<tr>
<td>4741a003-8952-4be4-9217-33a0ac327122</td>
<td>IndustryData-OutboundFlow.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read outbound data flows on behalf of the signed-in user.</td>
<td>View outbound flow definitions</td>
</tr>
<tr>
<td>aeb68e0b-e562-4a1f-b6dd-3484ad0cbb4b</td>
<td>IndustryData-OutboundFlow.ReadWrite.All</td>
<td>Global Administrator</td>
<td>Allows the app to read and write outbound data flows on behalf of the signed-in user.</td>
<td>Manage outbound flow definitions</td>
</tr>
<tr>
<td>a3f96ffe-cb84-40a8-ac85-582d7ef97c2a</td>
<td>IndustryData-ReferenceDefinition.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read reference definitions on behalf of the signed-in user.</td>
<td>View reference definitions</td>
</tr>
<tr>
<td>a757d430-be6d-430f-af57-28aabe79d247</td>
<td>IndustryData-ReferenceDefinition.ReadWrite.All</td>
<td>Global Administrator</td>
<td>Allows the app to read and write reference definitions on behalf of the signed-in user.</td>
<td>Manage reference definitions</td>
</tr>
<tr>
<td>92685235-50c4-4702-b2c8-36043db6fa79</td>
<td>IndustryData-Run.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read current and previous IndustryData runs on behalf of the signed-in user.</td>
<td>View current and previous runs</td>
</tr>
<tr>
<td>f03a6d0e-0989-460f-80b2-e57c8561763e</td>
<td>IndustryData-Run.Start</td>
<td>Global Administrator</td>
<td>Allows the app to view and start IndustryData runs on behalf of the signed-in user.</td>
<td>View and start runs</td>
</tr>
<tr>
<td>49b7016c-89ae-41e7-bd6f-b7170c5490bf</td>
<td>IndustryData-SourceSystem.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read source system definitions on behalf of the signed-in user.</td>
<td>View source system definitions</td>
</tr>
<tr>
<td>9599f005-05d6-4ea7-b1b1-4929768af5d0</td>
<td>IndustryData-SourceSystem.ReadWrite.All</td>
<td>Global Administrator</td>
<td>Allows the app to read and write source system definitions on behalf of the signed-in user.</td>
<td>Manage source system definitions</td>
</tr>
<tr>
<td>c9d51f28-8ccd-42b2-a836-fd8fe9ebf2ae</td>
<td>IndustryData-TimePeriod.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read time period definitions on behalf of the signed-in user.</td>
<td>Read time period definitions</td>
</tr>
<tr>
<td>b6d56528-3032-4f9d-830f-5a24a25e6661</td>
<td>IndustryData-TimePeriod.ReadWrite.All</td>
<td>Global Administrator</td>
<td>Allows the app to read and write time period definitions on behalf of the signed-in user.</td>
<td>Manage time period definitions</td>
</tr>
<tr>
<td>12f4bffb-b598-413c-984b-db99728f8b54</td>
<td>InformationProtectionConfig.Read</td>
<td>Global Reader</td>
<td>Allows the app to read the configurations applicable to the signed-in user for protecting organizational data, on behalf of the signed-in user.</td>
<td>Read configurations for protecting organizational data applicable to the user</td>
</tr>
<tr>
<td>7d249730-51a3-4180-8ec1-214f144f1bff</td>
<td>Insights-UserMetric.Read.All</td>
<td>Reports Reader</td>
<td>Allows an app to read user metrics insights, such as daily and monthly active users, on behalf of the signed-in user.</td>
<td>Read user metrics insights</td>
</tr>
<tr>
<td>ea4c1fd9-6a9f-4432-8e5d-86e06cc0da77</td>
<td>LearningContent.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read learning content in the organization&#39;s directory, on behalf of the signed-in user.</td>
<td>Read learning content</td>
</tr>
<tr>
<td>53cec1c4-a65f-4981-9dc1-ad75dbf1c077</td>
<td>LearningContent.ReadWrite.All</td>
<td>Directory Writers</td>
<td>Allows��the��app��to��manage learning��content��in��the��organization&#39;s��directory, on behalf of the signed-in user.</td>
<td>Manage��learning��content</td>
</tr>
<tr>
<td>dd8ce36f-9245-45ea-a99e-8ac398c22861</td>
<td>LearningProvider.Read</td>
<td>Directory Readers</td>
<td>Allows the app to read data for the learning provider in the organization&#39;s directory, on behalf of the signed-in user.</td>
<td>Read learning provider</td>
</tr>
<tr>
<td>40c2eb57-abaf-49f5-9331-e90fd01f7130</td>
<td>LearningProvider.ReadWrite</td>
<td>Directory Writers</td>
<td>Allows the app to create, update, read, and delete data for the learning provider in the organization&#39;s directory, on behalf of the signed-in user.</td>
<td>Manage��learning��provider</td>
</tr>
<tr>
<td>f55016cc-149c-447e-8f21-7cf3ec1d6350</td>
<td>LicenseAssignment.ReadWrite.All</td>
<td>License Administrator</td>
<td>Allows an app to manage license assignments for users and groups, on behalf of the signed-in user.</td>
<td>Manage all license assignments</td>
</tr>
<tr>
<td>2973a298-1d69-4f87-8d30-7025f0ec19d7</td>
<td>LifecycleWorkflows-CustomExt.Read.All</td>
<td>Lifecycle Workflows Administrator</td>
<td>Allows the app to read all Lifecycle workflows custom task extensions on behalf of a signed-in user.</td>
<td>Read all Lifecycle workflows custom task extensions</td>
</tr>
<tr>
<td>ef6bafb1-3019-4a22-a332-103aff92225f</td>
<td>LifecycleWorkflows-CustomExt.ReadWrite.All</td>
<td>Lifecycle Workflows Administrator</td>
<td>Allows the app to create, update, list, read and delete all Lifecycle workflows custom task extensions on behalf of a signed-in user.</td>
<td>Read and write all Lifecycle workflows custom task extensions</td>
</tr>
<tr>
<td>4d3d7f81-163f-426a-8432-5638d2e82083</td>
<td>LifecycleWorkflows-Reports.Read.All</td>
<td>Lifecycle Workflows Administrator</td>
<td>Allows the app to read all Lifecycle workflows reports on behalf of a signed-in user.</td>
<td>Read all Lifecycle workflows reports</td>
</tr>
<tr>
<td>df1c25b3-072c-45cd-8403-c63441e4cca1</td>
<td>LifecycleWorkflows-Workflow.Activate</td>
<td>Lifecycle Workflows Administrator</td>
<td>Allows the app to run workflows on-demand on behalf of a signed-in user.</td>
<td>Run workflows on-demand in Lifecycle workflows</td>
</tr>
<tr>
<td>7fabe5bd-2e47-4e61-b924-327117024e18</td>
<td>LifecycleWorkflows-Workflow.Read.All</td>
<td>Lifecycle Workflows Administrator</td>
<td>Allows the app to list and read all workflows and tasks on behalf of a signed-in user.</td>
<td>Read all workflows in Lifecycle workflows</td>
</tr>
<tr>
<td>789c445d-433c-4575-a1fc-367a58a1bd4a</td>
<td>LifecycleWorkflows-Workflow.ReadBasic.All</td>
<td>Lifecycle Workflows Administrator</td>
<td>Allows the app to list all workflows on behalf of a signed-in user.</td>
<td>List all workflows in Lifecycle workflows</td>
</tr>
<tr>
<td>29e49f0c-a053-4cc5-a4b1-7da0c8c1e643</td>
<td>LifecycleWorkflows-Workflow.ReadWrite.All</td>
<td>Lifecycle Workflows Administrator</td>
<td>Allows the app to create, update, list, read and delete all workflows and tasks in lifecycle workflows on behalf of a signed-in user.</td>
<td>Read and write all workflows in Lifecycle workflows</td>
</tr>
<tr>
<td>9bcb9916-765a-42af-bf77-02282e26b01a</td>
<td>LifecycleWorkflows.Read.All</td>
<td>Lifecycle Workflows Administrator</td>
<td>Allows the app to list and read all workflows, tasks and related lifecycle workflows resources on behalf of the signed-in user.</td>
<td>Read all lifecycle workflows resources</td>
</tr>
<tr>
<td>84b9d731-7db8-4454-8c90-fd9e95350179</td>
<td>LifecycleWorkflows.ReadWrite.All</td>
<td>Lifecycle Workflows Administrator</td>
<td>Allows the app to create, update, list, read and delete all workflows, tasks and related lifecycle workflows resources on behalf of the signed-in user.</td>
<td>Read and write all lifecycle workflows resources</td>
</tr>
<tr>
<td>d6d361b3-211a-4191-9fa7-15f72de4aac4</td>
<td>ListItems.SelectedOperations.Selected</td>
<td>User</td>
<td>Allow the application to access a subset of listitems on behalf of the signed in user.  The specific listitems and the permissions granted will be configured in SharePoint Online.</td>
<td>Access selected ListItems, on behalf of the signed-in user</td>
</tr>
<tr>
<td>033b51ee-d6fa-4add-b627-ee680c7212b5</td>
<td>Lists.SelectedOperations.Selected</td>
<td>User</td>
<td>Allow the application to access a subset of lists on behalf of the signed in user.  The specific lists and the permissions granted will be configured in SharePoint Online.</td>
<td>Access selected Lists, on behalf of the signed-in user</td>
</tr>
<tr>
<td>df96e8a0-f4e1-4ecf-8d83-a429f822cbd6</td>
<td>MailboxItem.ImportExport</td>
<td>Exchange Administrator</td>
<td>Allows the app to backup, restore, and modify mailbox items on behalf of the signed-in user.</td>
<td>Allows the app to perform backup and restore of mailbox items</td>
</tr>
<tr>
<td>dc34164e-6c4a-41a0-be89-3ae2fbad7cd3</td>
<td>ManagedTenants.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read all managed tenant information on behalf of the signed-in user.</td>
<td>Read all managed tenant information</td>
</tr>
<tr>
<td>b31fa710-c9b3-4d9e-8f5e-8036eecddab9</td>
<td>ManagedTenants.ReadWrite.All</td>
<td>Global Reader</td>
<td>Allows the app to read and write all managed tenant information on behalf of the signed-in user.</td>
<td>Read and write all managed tenant information</td>
</tr>
<tr>
<td>f6a3db3e-f7e8-4ed2-a414-557c8c9830be</td>
<td>Member.Read.Hidden</td>
<td>Directory Readers</td>
<td>Allows the app to read the memberships of hidden groups and administrative units on behalf of the signed-in user, for those hidden groups and administrative units that the signed-in user has access to.</td>
<td>Read hidden memberships</td>
</tr>
<tr>
<td>526aa72a-5878-49fe-bf4e-357973af9b06</td>
<td>MultiTenantOrganization.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read multi-tenant organization details and tenants on behalf of the signed-in user.</td>
<td>Read multi-tenant organization details and tenants</td>
</tr>
<tr>
<td>77af1528-84f3-4023-8d90-d219cd433108</td>
<td>MultiTenantOrganization.ReadWrite.All</td>
<td>User Administrator</td>
<td>Allows the app to read and write multi-tenant organization details and tenants on behalf of the signed-in user.</td>
<td>Read and write multi-tenant organization details and tenants</td>
</tr>
<tr>
<td>51ae584e-e736-4718-897b-10af70f8e3cc</td>
<td>MutualTlsOauthConfiguration.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read configuration used for OAuth 2.0 mutual-TLS client authentication, on behalf of the signed-in user. This includes reading trusted certificate authorities.</td>
<td>Read all configurations used for mutual-TLS client authentication.</td>
</tr>
<tr>
<td>a51115bc-f64f-498f-bcee-00dcd28f4a03</td>
<td>MutualTlsOauthConfiguration.ReadWrite.All</td>
<td>Global Reader</td>
<td>Allows the app to read and update configuration used for OAuth 2.0 mutual-TLS client authentication, on behalf of the signed-in user. This includes adding and updating trusted certificate authorities.</td>
<td>Read and write all configurations used for mutual-TLS client authentication.</td>
</tr>
<tr>
<td>b0c61509-cfc3-42bd-9bd4-66d81785fee4</td>
<td>NetworkAccess-Reports.Read.All</td>
<td>Global Secure Access Log Reader</td>
<td>Allows the app to read all network access reports on behalf of the signed-in user.</td>
<td>Read all network access reports</td>
</tr>
<tr>
<td>2f7013e0-ab4e-447f-a5e1-5d419950692d</td>
<td>NetworkAccess.Read.All</td>
<td>Global Secure Access Administrator</td>
<td>Allows the app to read all network access information on behalf of the signed-in user.</td>
<td>Read all network access information</td>
</tr>
<tr>
<td>ae2df9c5-f18d-4ec4-a51b-bdeb807f177b</td>
<td>NetworkAccess.ReadWrite.All</td>
<td>Network Administrator</td>
<td>Allows the app to read and write all network access information and configuration settings on behalf of the signed-in user.</td>
<td>Read and write all network access information</td>
</tr>
<tr>
<td>b8a36cc2-b810-461a-baa4-a7281e50bd5c</td>
<td>NetworkAccessBranch.ReadWrite.All</td>
<td>Network Administrator</td>
<td>Allows the app to read and write your organization&#39;s branches for network access on behalf of the signed-in user.</td>
<td>Read and write properties of branches for network access</td>
</tr>
<tr>
<td>b1fbad0f-ef6e-42ed-8676-bca7fa3e7291</td>
<td>NetworkAccessPolicy.ReadWrite.All</td>
<td>Network Administrator</td>
<td>Allows the app to read and write your organization&#39;s security and routing network access policies on behalf of the signed-in user.</td>
<td>Read and write security and routing policies for network access</td>
</tr>
<tr>
<td>166741d6-eeb8-46fe-91f4-817d2af7bc88</td>
<td>OnlineMeetingAiInsight.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read all AI Insights for online meetings, on behalf of the signed-in user.</td>
<td>Read all AI Insights for online meetings.</td>
</tr>
<tr>
<td>190c2bb6-1fdd-4fec-9aa2-7d571b5e1fe3</td>
<td>OnlineMeetingRecording.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read all recordings of online meetings, on behalf of the signed-in user.</td>
<td>Read all recordings of online meetings.</td>
</tr>
<tr>
<td>30b87d18-ebb1-45db-97f8-82ccb1f0190c</td>
<td>OnlineMeetingTranscript.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read all transcripts of online meetings, on behalf of the signed-in user.</td>
<td>Read all transcripts of online meetings.</td>
</tr>
<tr>
<td>f6609722-4100-44eb-b747-e6ca0536989d</td>
<td>OnPremDirectorySynchronization.Read.All</td>
<td>Directory Synchronization Accounts</td>
<td>Allows the app to read all on-premises directory synchronization information for the organization, on behalf of the signed-in user.</td>
<td>Read all on-premises directory synchronization information</td>
</tr>
<tr>
<td>c2d95988-7604-4ba1-aaed-38a5f82a51c7</td>
<td>OnPremDirectorySynchronization.ReadWrite.All</td>
<td>Hybrid Identity Administrator</td>
<td>Allows the app to read and write all on-premises directory synchronization information for the organization, on behalf of the signed-in user.</td>
<td>Read and write all on-premises directory synchronization information</td>
</tr>
<tr>
<td>8c4d5184-71c2-4bf8-bb9d-bc3378c9ad42</td>
<td>OnPremisesPublishingProfiles.ReadWrite.All</td>
<td>Hybrid Identity Administrator</td>
<td>Allows the app to manage hybrid identity service configuration by creating, viewing, updating and deleting on-premises published resources, on-premises agents and agent groups, on behalf of the signed-in user.</td>
<td>Manage on-premises published resources</td>
</tr>
<tr>
<td>4908d5b9-3fb2-4b1e-9336-1888b7937185</td>
<td>Organization.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read the organization and related resources, on behalf of the signed-in user.��Related resources include things like subscribed skus and tenant branding information.</td>
<td>Read organization information</td>
</tr>
<tr>
<td>46ca0847-7e6b-426e-9775-ea810a948356</td>
<td>Organization.ReadWrite.All</td>
<td>Organizational Branding Administrator</td>
<td>Allows the app to read and write the organization and related resources, on behalf of the signed-in user.��Related resources include things like subscribed skus and tenant branding information.</td>
<td>Read and write organization information</td>
</tr>
<tr>
<td>9082f138-6f02-4f3a-9f4d-5f3c2ce5c688</td>
<td>OrganizationalBranding.Read.All</td>
<td>Organizational Branding Administrator</td>
<td>Allows the app to read the organizational branding information, on behalf of the signed-in user.</td>
<td>Read organizational branding information</td>
</tr>
<tr>
<td>15ce63de-b141-4c9a-a9a5-241bf27c6aaf</td>
<td>OrganizationalBranding.ReadWrite.All</td>
<td>Organizational Branding Administrator</td>
<td>Allows the app to read and write the organizational branding information, on behalf of the signed-in user.</td>
<td>Read and write organizational branding information</td>
</tr>
<tr>
<td>08432d1b-5911-483c-86df-7980af5cdee0</td>
<td>OrgContact.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read all organizational contacts on behalf of the signed-in user. ��These contacts are managed by the organization and are different from a user&#39;s personal contacts.</td>
<td>Read organizational contacts</td>
</tr>
<tr>
<td>1e9b7a7e-4d64-44ff-acf5-2e9651c1519f</td>
<td>OrgSettings-AppsAndServices.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read organization-wide apps and services settings on behalf of the signed-in user.</td>
<td>Read organization-wide apps and services settings</td>
</tr>
<tr>
<td>c167b0e7-47c0-48e8-9eee-9892f58018fa</td>
<td>OrgSettings-AppsAndServices.ReadWrite.All</td>
<td>Global Administrator</td>
<td>Allows the app to read and write organization-wide apps and services settings on behalf of the signed-in user.</td>
<td>Read and write organization-wide apps and services settings</td>
</tr>
<tr>
<td>9862d930-5aec-4a98-8d4f-7277a8db9bcb</td>
<td>OrgSettings-DynamicsVoice.Read.All</td>
<td>Dynamics 365 Administrator</td>
<td>Allows the app to read organization-wide Dynamics customer voice settings on behalf of the signed-in user.</td>
<td>Read organization-wide Dynamics customer voice settings</td>
</tr>
<tr>
<td>4cea26fb-6967-4234-82c4-c044414743f8</td>
<td>OrgSettings-DynamicsVoice.ReadWrite.All</td>
<td>Dynamics 365 Administrator</td>
<td>Allows the app to read and write organization-wide Dynamics customer voice settings on behalf of the signed-in user.</td>
<td>Read and write organization-wide Dynamics customer voice settings</td>
</tr>
<tr>
<td>210051a0-1ffc-435c-ae76-02d226d05752</td>
<td>OrgSettings-Forms.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read organization-wide Microsoft Forms settings on behalf of the signed-in user.</td>
<td>Read organization-wide Microsoft Forms settings</td>
</tr>
<tr>
<td>346c19ff-3fb2-4e81-87a0-bac9e33990c1</td>
<td>OrgSettings-Forms.ReadWrite.All</td>
<td>Global Reader</td>
<td>Allows the app to read and write organization-wide Microsoft Forms settings on behalf of the signed-in user.</td>
<td>Read and write organization-wide Microsoft Forms settings</td>
</tr>
<tr>
<td>8cbdb9f6-9c2e-451a-814d-ec606e5d0212</td>
<td>OrgSettings-Microsoft365Install.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read organization-wide Microsoft 365 apps installation settings on behalf of the signed-in user.</td>
<td>Read organization-wide Microsoft 365 apps installation settings</td>
</tr>
<tr>
<td>1ff35e91-19eb-42d8-aa2d-cc9891127ae5</td>
<td>OrgSettings-Microsoft365Install.ReadWrite.All</td>
<td>Office Apps Administrator</td>
<td>Allows the app to read and write organization-wide Microsoft 365 apps installation settings on behalf of the signed-in user.</td>
<td>Read and write organization-wide Microsoft 365 apps installation settings</td>
</tr>
<tr>
<td>7ff96f41-f022-45ba-acd8-ef3f03063d6b</td>
<td>OrgSettings-Todo.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read organization-wide Microsoft To Do settings on behalf of the signed-in user.</td>
<td>Read organization-wide Microsoft To Do settings</td>
</tr>
<tr>
<td>087502c2-5263-433e-abe3-8f77231a0627</td>
<td>OrgSettings-Todo.ReadWrite.All</td>
<td>Global Reader</td>
<td>Allows the app to read and write organization-wide Microsoft To Do settings on behalf of the signed-in user.</td>
<td>Read and write organization-wide Microsoft To Do settings</td>
</tr>
<tr>
<td>8804798e-5934-4e30-8ce3-ef88257cecd4</td>
<td>PartnerBilling.Read.All</td>
<td>Billing Administrator</td>
<td>Allows the app to read all of billing data from Microsoft for your company&#39;s tenant, on behalf of the signed-in user. This includes reading billed and unbilled Usage and Invoice reconciliation data.</td>
<td>Read all billing data for your company&#39;s tenant</td>
</tr>
<tr>
<td>5567b981-0bf1-4796-9038-0648b46e116d</td>
<td>PartnerSecurity.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read security alerts of customer with CSP relationship on behalf of the partner signed-in user.</td>
<td>Read security alerts of customer with CSP relationship</td>
</tr>
<tr>
<td>0cd2c1f6-94a1-4075-ab8c-0b1aff2e1ad5</td>
<td>PartnerSecurity.ReadWrite.All</td>
<td>Partner Tier1 Support</td>
<td>Allows the app to read security alerts and update status of alerts of customer with CSP relationship on behalf of the partner signed-in user.</td>
<td>Read security alerts and update status of security alerts of customer with CSP relationship</td>
</tr>
<tr>
<td>d88fd3fb-53d3-4c1c-8c39-787fcac2ed7a</td>
<td>PendingExternalUserProfile.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read available properties of pending external user profiles, on behalf of the signed-in user.</td>
<td>Read pending external user profiles</td>
</tr>
<tr>
<td>93a1fb28-c908-4826-904e-0c74ad352b73</td>
<td>PendingExternalUserProfile.ReadWrite.All</td>
<td>User Administrator</td>
<td>Allows the app to read and write available properties of pending external user profiles, on behalf of the signed-in user.</td>
<td>Read and write pending external user profiles</td>
</tr>
<tr>
<td>b89f9189-71a5-4e70-b041-9887f0bc7e4a</td>
<td>People.Read.All</td>
<td>People Administrator</td>
<td>Allows the app to read a scored list of relevant people of the signed-in user or other users in the signed-in user&#39;s organization. The list can include local contacts, contacts from social networking, your organization&#39;s directory, and people from recent communications (such as email and Skype).</td>
<td>Read all users&#39; relevant people lists</td>
</tr>
<tr>
<td>ec762c5f-388b-4b16-8693-ac1efbc611bc</td>
<td>PeopleSettings.Read.All</td>
<td>People Administrator</td>
<td>Allows the application to read tenant-wide people settings on behalf of the signed-in user.</td>
<td>Read tenant-wide people settings</td>
</tr>
<tr>
<td>e67e6727-c080-415e-b521-e3f35d5248e9</td>
<td>PeopleSettings.ReadWrite.All</td>
<td>People Administrator</td>
<td>Allows the application to read and write tenant-wide people settings on behalf of the signed-in user.</td>
<td>Read and write tenant-wide people settings</td>
</tr>
<tr>
<td>cb8f45a0-5c2e-4ea1-b803-84b870a7d7ec</td>
<td>Place.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read your company&#39;s places (conference rooms and room lists) for calendar events and other applications, on behalf of the signed-in user.</td>
<td>Read all company places</td>
</tr>
<tr>
<td>4c06a06a-098a-4063-868e-5dfee3827264</td>
<td>Place.ReadWrite.All</td>
<td>Exchange Administrator</td>
<td>Allows the app to manage organization places (conference rooms and room lists) for calendar events and other applications, on behalf of the signed-in user.</td>
<td>Read and write organization places</td>
</tr>
<tr>
<td>4c7f93d2-6b0b-4e05-91aa-87842f0a2142</td>
<td>PlaceDevice.Read.All</td>
<td>Cloud Device Administrator</td>
<td>Allows the app to read all workplace devices, on behalf of the signed-in user.</td>
<td>Read all workplace devices</td>
</tr>
<tr>
<td>eafd6a71-e95a-4f8a-bb6e-fb84ab7fbd9e</td>
<td>PlaceDevice.ReadWrite.All</td>
<td>Cloud Device Administrator</td>
<td>Allows the app to read and write all workplace devices, on behalf of the signed-in user.</td>
<td>Read and write all workplace devices</td>
</tr>
<tr>
<td>572fea84-0151-49b2-9301-11cb16974376</td>
<td>Policy.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read your organization&#39;s policies on behalf of the signed-in user.</td>
<td>Read your organization&#39;s policies</td>
</tr>
<tr>
<td>3616a4b0-6746-49c4-a678-4c237599074d</td>
<td>Policy.Read.DeviceConfiguration</td>
<td>Global Reader</td>
<td>Allows the app to read your organization&#39;s device configuration policies on behalf of the signed-in user.  For example, device registration policy can limit initial provisioning controls using quota restrictions, additional authentication and authorization checks.</td>
<td>Read your organization&#39;s device configuration policies</td>
</tr>
<tr>
<td>d146432f-b803-4ed4-8d42-ba74193a6ede</td>
<td>Policy.Read.IdentityProtection</td>
<td>Security Reader</td>
<td>Allows the app to read your organization�??s identity protection policy on behalf of the signed-in user.</td>
<td>Read your organization�??s identity protection policy</td>
</tr>
<tr>
<td>414de6ea-2d92-462f-b120-6e2a809a6d01</td>
<td>Policy.Read.PermissionGrant</td>
<td>Global Reader</td>
<td>Allows the app to read policies related to consent and permission grants for applications, on behalf of the signed-in user.</td>
<td>Read consent and permission grant policies</td>
</tr>
<tr>
<td>4f5bc9c8-ea54-4772-973a-9ca119cb0409</td>
<td>Policy.ReadWrite.AccessReview</td>
<td>Identity Governance Administrator</td>
<td>Allows the app to read and write your organization&#39;s directory access review default policy on behalf of the signed-in user.</td>
<td>Read and write your organization&#39;s directory access review default policy</td>
</tr>
<tr>
<td>b27add92-efb2-4f16-84f5-8108ba77985c</td>
<td>Policy.ReadWrite.ApplicationConfiguration</td>
<td>Application Administrator</td>
<td>Allows the app to read and write your organization&#39;s application configuration policies on behalf of the signed-in user.  This includes policies such as activityBasedTimeoutPolicy, claimsMappingPolicy, homeRealmDiscoveryPolicy,  tokenIssuancePolicy and tokenLifetimePolicy.</td>
<td>Read and write your organization&#39;s application configuration policies</td>
</tr>
<tr>
<td>edb72de9-4252-4d03-a925-451deef99db7</td>
<td>Policy.ReadWrite.AuthenticationFlows</td>
<td>Authentication Policy Administrator</td>
<td>Allows the app to read and write the authentication flow policies, on behalf of the signed-in user.</td>
<td>Read and write authentication flow policies</td>
</tr>
<tr>
<td>7e823077-d88e-468f-a337-e18f1f0e6c7c</td>
<td>Policy.ReadWrite.AuthenticationMethod</td>
<td>Authentication Policy Administrator</td>
<td>Allows the app to read and write the authentication method policies, on behalf of the signed-in user.��</td>
<td>Read and write authentication method policies</td>
</tr>
<tr>
<td>edd3c878-b384-41fd-95ad-e7407dd775be</td>
<td>Policy.ReadWrite.Authorization</td>
<td>Authentication Policy Administrator</td>
<td>Allows the app to read and write your organization&#39;s authorization policy on behalf of the signed-in user.  For example, authorization policies can control some of the permissions that the out-of-the-box user role has by default.</td>
<td>Read and write your organization&#39;s authorization policy</td>
</tr>
<tr>
<td>ad902697-1014-4ef5-81ef-2b4301988e8c</td>
<td>Policy.ReadWrite.ConditionalAccess</td>
<td>Conditional Access Administrator</td>
<td>Allows the app to read and write your organization&#39;s conditional access policies on behalf of the signed-in user.</td>
<td>Read and write your organization&#39;s conditional access policies</td>
</tr>
<tr>
<td>4d135e65-66b8-41a8-9f8b-081452c91774</td>
<td>Policy.ReadWrite.ConsentRequest</td>
<td>Application Administrator</td>
<td>Allows the app to read and write your organization&#39;s consent requests policy on behalf of the signed-in user.</td>
<td>Read and write consent request policy</td>
</tr>
<tr>
<td>014b43d0-6ed4-4fc6-84dc-4b6f7bae7d85</td>
<td>Policy.ReadWrite.CrossTenantAccess</td>
<td>Conditional Access Administrator</td>
<td>Allows the app to read and write your organization&#39;s cross tenant access policies on behalf of the signed-in user.</td>
<td>Read and write your organization&#39;s cross tenant access policies</td>
</tr>
<tr>
<td>9ef7463f-1d39-406f-89ea-3483a4645e1c</td>
<td>Policy.ReadWrite.CrossTenantCapability</td>
<td>Global Administrator</td>
<td>Allows the app to read and write your organization&#39;s M365 cross tenant access capabilities on behalf of the signed-in user.</td>
<td>Read and write your organization&#39;s M365 cross tenant access capabilities</td>
</tr>
<tr>
<td>40b534c3-9552-4550-901b-23879c90bcf9</td>
<td>Policy.ReadWrite.DeviceConfiguration</td>
<td>Intune Administrator</td>
<td>Allows the app to read and write your organization&#39;s device configuration policies on behalf of the signed-in user.  For example, device registration policy can limit initial provisioning controls using quota restrictions, additional authentication and authorization checks.</td>
<td>Read and write your organization&#39;s device configuration policies</td>
</tr>
<tr>
<td>b5219784-1215-45b5-b3f1-88fe1081f9c0</td>
<td>Policy.ReadWrite.ExternalIdentities</td>
<td>Global Administrator</td>
<td>Allows the application to read and update the organization&#39;s external identities policy on behalf of the signed-in user.  For example, external identities policy controls if users invited to access resources in your organization via B2B collaboration or B2B direct connect are allowed to self-service leave.</td>
<td>Read and write your organization&#39;s external identities policy</td>
</tr>
<tr>
<td>92a38652-f13b-4875-bc77-6e1dbb63e1b2</td>
<td>Policy.ReadWrite.FeatureRollout</td>
<td>User Administrator</td>
<td>Allows the app to read and write your organization&#39;s feature rollout policies on behalf of the signed-in user. Includes abilities to assign and remove users and groups to rollout of a specific feature.</td>
<td>Read and write your organization&#39;s feature rollout policies</td>
</tr>
<tr>
<td>be1be369-4540-4ac9-8928-79de99f70d8f</td>
<td>Policy.ReadWrite.FedTokenValidation</td>
<td>Global Administrator</td>
<td>Allows the application to read and update the organization&#39;s federated token validation policy on behalf of the signed-in user.</td>
<td>Read and write your organization&#39;s federated token validation policy</td>
</tr>
<tr>
<td>7256e131-3efb-4323-9854-cf41c6021770</td>
<td>Policy.ReadWrite.IdentityProtection</td>
<td>Security Administrator</td>
<td>Allows the app to read and write your organization�??s identity protection policy on behalf of the signed-in user.</td>
<td>Read and write your organization�??s identity protection policy </td>
</tr>
<tr>
<td>a8ead177-1889-4546-9387-f25e658e2a79</td>
<td>Policy.ReadWrite.MobilityManagement</td>
<td>Intune Administrator</td>
<td>Allows the app to read and write your organization&#39;s mobility management policies on behalf of the signed-in user.  For example, a mobility management policy can set the enrollment scope for a given mobility management application.</td>
<td>Read and write your organization&#39;s mobility management policies</td>
</tr>
<tr>
<td>2672f8bb-fd5e-42e0-85e1-ec764dd2614e</td>
<td>Policy.ReadWrite.PermissionGrant</td>
<td>Permissions Management Administrator</td>
<td>Allows the app to manage policies related to consent and permission grants for applications, on behalf of the signed-in user.</td>
<td>Manage consent and permission grant policies</td>
</tr>
<tr>
<td>0b2a744c-2abf-4f1e-ad7e-17a087e2be99</td>
<td>Policy.ReadWrite.SecurityDefaults</td>
<td>Conditional Access Administrator</td>
<td>Allows the app to read and write your organization&#39;s security defaults policy on behalf of the signed-in user.</td>
<td>Read and write your organization&#39;s security defaults policy</td>
</tr>
<tr>
<td>cefba324-1a70-4a6e-9c1d-fd670b7ae392</td>
<td>Policy.ReadWrite.TrustFramework</td>
<td>Global Administrator</td>
<td>Allows the app to read and write your organization&#39;s trust framework policies on behalf of the signed-in user.</td>
<td>Read and write your organization&#39;s trust framework policies</td>
</tr>
<tr>
<td>d69c2d6d-4f72-4f99-a6b9-663e32f8cf68</td>
<td>PrintConnector.Read.All</td>
<td>Printer Administrator</td>
<td>Allows the application to read print connectors on behalf of the signed-in user.</td>
<td>Read print connectors</td>
</tr>
<tr>
<td>79ef9967-7d59-4213-9c64-4b10687637d8</td>
<td>PrintConnector.ReadWrite.All</td>
<td>Printer Administrator</td>
<td>Allows the application to read and write print connectors on behalf of the signed-in user.</td>
<td>Read and write print connectors</td>
</tr>
<tr>
<td>90c30bed-6fd1-4279-bf39-714069619721</td>
<td>Printer.Create</td>
<td>Printer Administrator</td>
<td>Allows the application to create (register) printers on behalf of the signed-in user.��</td>
<td>Register printers�?��</td>
</tr>
<tr>
<td>93dae4bd-43a1-4a23-9a1a-92957e1d9121</td>
<td>Printer.FullControl.All</td>
<td>Printer Administrator</td>
<td>Allows the application to create (register), read, update, and delete (unregister) printers on behalf of the signed-in user.��</td>
<td>Register, read, update, and unregister printers</td>
</tr>
<tr>
<td>3a736c8a-018e-460a-b60c-863b2683e8bf</td>
<td>Printer.Read.All</td>
<td>Printer Administrator</td>
<td>Allows the application to read printers on behalf of the signed-in user.��</td>
<td>Read printers</td>
</tr>
<tr>
<td>89f66824-725f-4b8f-928e-e1c5258dc565</td>
<td>Printer.ReadWrite.All</td>
<td>Printer Administrator</td>
<td>Allows the application to read and update printers on behalf of the signed-in user.��Does not allow creating (registering) or deleting (unregistering) printers.</td>
<td>Read and update printers</td>
</tr>
<tr>
<td>06ceea37-85e2-40d7-bec3-91337a46038f</td>
<td>PrinterShare.ReadWrite.All</td>
<td>Printer Administrator</td>
<td>Allows the application to read and update printer shares on behalf of the signed-in user.��</td>
<td>Read and write printer shares</td>
</tr>
<tr>
<td>afdd6933-a0d8-40f7-bd1a-b5d778e8624b</td>
<td>PrintJob.Read.All</td>
<td>Printer Administrator</td>
<td>Allows the application to read the metadata and document content of print jobs on behalf of the signed-in user.��</td>
<td>Read print jobs</td>
</tr>
<tr>
<td>04ce8d60-72ce-4867-85cf-6d82f36922f3</td>
<td>PrintJob.ReadBasic.All</td>
<td>Helpdesk Administrator</td>
<td>Allows the application to read the metadata of print jobs on behalf of the signed-in user.��Does not allow access to print job document content.</td>
<td>Read basic information of print jobs</td>
</tr>
<tr>
<td>036b9544-e8c5-46ef-900a-0646cc42b271</td>
<td>PrintJob.ReadWrite.All</td>
<td>Printer Administrator</td>
<td>Allows the application to read and update the metadata and document content of print jobs on behalf of the signed-in user.��</td>
<td>Read and write print jobs</td>
</tr>
<tr>
<td>3a0db2f6-0d2a-4c19-971b-49109b19ad3d</td>
<td>PrintJob.ReadWriteBasic.All</td>
<td>Printer Administrator</td>
<td>Allows the application to read and update the metadata of print jobs on behalf of the signed-in user.��Does not allow access to print job document content.</td>
<td>Read and write basic information of print jobs</td>
</tr>
<tr>
<td>490f32fd-d90f-4dd7-a601-ff6cdc1a3f6c</td>
<td>PrintSettings.Read.All</td>
<td>Printer Administrator</td>
<td>Allows the application to read tenant-wide print settings on behalf of the signed-in user.</td>
<td>Read tenant-wide print settings</td>
</tr>
<tr>
<td>9ccc526a-c51c-4e5c-a1fd-74726ef50b8f</td>
<td>PrintSettings.ReadWrite.All</td>
<td>Printer Administrator</td>
<td>Allows the application to read and write tenant-wide print settings on behalf of the signed-in user.</td>
<td>Read and write tenant-wide print settings</td>
</tr>
<tr>
<td>b3a539c9-59cb-4ad5-825a-041ddbdc2bdb</td>
<td>PrivilegedAccess.Read.AzureAD</td>
<td>Global Reader</td>
<td>Allows the app to read time-based assignment and just-in-time elevation (including scheduled elevation) of Azure AD built-in and custom administrative roles, on behalf of the signed-in user.</td>
<td>Read privileged access to Azure AD</td>
</tr>
<tr>
<td>d329c81c-20ad-4772-abf9-3f6fdb7e5988</td>
<td>PrivilegedAccess.Read.AzureADGroup</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to read time-based assignment and just-in-time elevation (including scheduled elevation) of Azure AD groups, on behalf of the signed-in user.</td>
<td>Read privileged access to Azure AD groups</td>
</tr>
<tr>
<td>1d89d70c-dcac-4248-b214-903c457af83a</td>
<td>PrivilegedAccess.Read.AzureResources</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to read time-based assignment and just-in-time elevation of Azure resources (like your subscriptions, resource groups, storage, compute) on behalf of the signed-in user.</td>
<td>Read privileged access to Azure resources</td>
</tr>
<tr>
<td>3c3c74f5-cdaa-4a97-b7e0-4e788bfcfb37</td>
<td>PrivilegedAccess.ReadWrite.AzureAD</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to request and manage just in time elevation (including scheduled elevation) of users to Azure AD built-in administrative roles, on behalf of signed-in users.</td>
<td>Read and write privileged access to Azure AD</td>
</tr>
<tr>
<td>32531c59-1f32-461f-b8df-6f8a3b89f73b</td>
<td>PrivilegedAccess.ReadWrite.AzureADGroup</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to request and manage time-based assignment and just-in-time elevation (including scheduled elevation) of Azure AD groups, on behalf of the signed-in user.</td>
<td>Read and write privileged access to Azure AD groups</td>
</tr>
<tr>
<td>a84a9652-ffd3-496e-a991-22ba5529156a</td>
<td>PrivilegedAccess.ReadWrite.AzureResources</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to request and manage time-based assignment and just-in-time elevation of user privileges to manage Azure resources (like subscriptions, resource groups, storage, compute) on behalf of the signed-in users.</td>
<td>Read and write privileged access to Azure resources</td>
</tr>
<tr>
<td>02a32cc4-7ab5-4b58-879a-0586e0f7c495</td>
<td>PrivilegedAssignmentSchedule.Read.AzureADGroup</td>
<td>Groups Administrator</td>
<td>Allows the app to read time-based assignment schedules for access to Azure AD groups, on behalf of the signed-in user.</td>
<td>Read assignment schedules for access to Azure AD groups</td>
</tr>
<tr>
<td>06dbc45d-6708-4ef0-a797-f797ee68bf4b</td>
<td>PrivilegedAssignmentSchedule.ReadWrite.AzureADGroup</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to read, create, and delete time-based assignment schedules for access to Azure AD groups, on behalf of the signed-in user.</td>
<td>Read, create, and delete assignment schedules for access to Azure AD groups</td>
</tr>
<tr>
<td>ca5fe595-68ff-4dfd-907d-4509501a0e49</td>
<td>PrivilegedAssignmentSchedule.Remove.AzureADGroup</td>
<td>Groups Administrator</td>
<td>Allows the app to delete time-based assignment schedules for access to Azure AD groups, on behalf of the signed-in user.</td>
<td>Delete assignment schedules for access to Azure AD groups</td>
</tr>
<tr>
<td>8f44f93d-ecef-46ae-a9bf-338508d44d6b</td>
<td>PrivilegedEligibilitySchedule.Read.AzureADGroup</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to read time-based eligibility schedules for access to Azure AD groups, on behalf of the signed-in user.</td>
<td>Read eligibility schedules for access to Azure AD groups</td>
</tr>
<tr>
<td>ba974594-d163-484e-ba39-c330d5897667</td>
<td>PrivilegedEligibilitySchedule.ReadWrite.AzureADGroup</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to read, create, and delete time-based eligibility schedules for access to Azure AD groups, on behalf of the signed-in user.</td>
<td>Read, create, and delete eligibility schedules for access to Azure AD groups</td>
</tr>
<tr>
<td>c5ea9ab4-9b41-4c09-a400-53e652fb5096</td>
<td>PrivilegedEligibilitySchedule.Remove.AzureADGroup</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to delete time-based eligibility schedules for access to Azure AD groups, on behalf of the signed-in user.</td>
<td>Delete eligibility schedules for access to Azure AD groups</td>
</tr>
<tr>
<td>469cd065-729e-4dee-b1fa-d92e0fab6310</td>
<td>ProfilePhoto.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read all profile photos of users and groups, on behalf of the signed-in user.</td>
<td>Read profile photo of a user or group</td>
</tr>
<tr>
<td>f5b24df7-511e-48bb-ae88-643f023b55e1</td>
<td>ProfilePhoto.ReadWrite.All</td>
<td>User Administrator</td>
<td>Allows the app to read and write all profile photos of users and groups, on behalf of the signed-in user.</td>
<td>Read and write profile photo of a user or group</td>
</tr>
<tr>
<td>c492a2e1-2f8f-4caa-b076-99bbf6e40fe4</td>
<td>ProgramControl.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read programs and program controls that the signed-in user has access to in the organization.</td>
<td>Read all programs that user can access</td>
</tr>
<tr>
<td>50fd364f-9d93-4ae1-b170-300e87cccf84</td>
<td>ProgramControl.ReadWrite.All</td>
<td>Application Administrator</td>
<td>Allows the app to read, update, delete and perform actions on programs and program controls that the signed-in user has access to in the organization.</td>
<td>Manage all programs that user can access</td>
</tr>
<tr>
<td>04a4b2a2-3f26-4fc8-87ee-9c46e68db175</td>
<td>PublicKeyInfrastructure.Read.All</td>
<td>Global Reader</td>
<td>Allows the application to read certificate-based authentication configuration such as all public key infrastructures (PKI) and certificate authorities (CA) configured for the organization, on behalf of the signed-in user.</td>
<td>Read certificate based authentication configurations</td>
</tr>
<tr>
<td>3591b7f3-dba8-4bad-b667-7a64bd4f2b83</td>
<td>PublicKeyInfrastructure.ReadWrite.All</td>
<td>Privileged Role Administrator</td>
<td>Allows the application to read  and write certificate-based authentication configuration such as all public key infrastructures (PKI) and certificate authorities (CA) configured for the organization, on behalf of the signed-in user.</td>
<td>Read and write certificate based authentication configurations</td>
</tr>
<tr>
<td>07f995eb-fc67-4522-ad66-2b8ca8ea3efd</td>
<td>RecordsManagement.Read.All</td>
<td>Global Reader</td>
<td>Allows the application to read any data from Records Management, such as configuration, labels, and policies on behalf of the signed-in user.</td>
<td>Read Records Management configuration,��labels, and policies</td>
</tr>
<tr>
<td>f2833d75-a4e6-40ab-86d4-6dfe73c97605</td>
<td>RecordsManagement.ReadWrite.All</td>
<td>Compliance Administrator</td>
<td>Allow the application to create, update and delete any data from Records Management, such as configuration, labels, and policies on behalf of the signed-in user.</td>
<td>Read and write Records Management configuration, labels, and policies</td>
</tr>
<tr>
<td>02e97553-ed7b-43d0-ab3c-f8bace0d040c</td>
<td>Reports.Read.All</td>
<td>Reports Reader</td>
<td>Allows an app to read all service usage reports on behalf of the signed-in user.  Services that provide usage reports include Office 365 and Azure Active Directory.</td>
<td>Read all usage reports</td>
</tr>
<tr>
<td>84fac5f4-33a9-4100-aa38-a20c6d29e5e7</td>
<td>ReportSettings.Read.All</td>
<td>Reports Reader</td>
<td>Allows the app to read admin report settings, such as whether to display concealed information in reports, on behalf of the signed-in user</td>
<td>Read admin report settings</td>
</tr>
<tr>
<td>b955410e-7715-4a88-a940-dfd551018df3</td>
<td>ReportSettings.ReadWrite.All</td>
<td>Reports Reader</td>
<td>Allows the app to read and update admin report settings, such as whether to display concealed information in reports, on behalf of the signed-in user.</td>
<td>Read and write admin report settings</td>
</tr>
<tr>
<td>cb530fca-534b-4e72-aa74-bca7e8bbd06f</td>
<td>ResourceSpecificPermissionGrant.ReadForChat</td>
<td>Global Reader</td>
<td>Allows the app to read the resource specific permissions granted on the chat, on behalf of the signed-in user.</td>
<td>Read resource specific permissions granted on a chat</td>
</tr>
<tr>
<td>eafad40c-bf7a-415a-b7f8-acdf5706b58f</td>
<td>ResourceSpecificPermissionGrant.ReadForTeam</td>
<td>Global Reader</td>
<td>Allows the app to read the resource specific permissions granted on the team, on behalf of the signed-in user.</td>
<td>Read resource specific permissions granted on a team</td>
</tr>
<tr>
<td>f1d91a8f-88e7-4774-8401-b668d5bca0c5</td>
<td>ResourceSpecificPermissionGrant.ReadForUser</td>
<td>Reports Reader</td>
<td>Allows the app to read the resource specific permissions granted on a user account, on behalf of the signed-in user.</td>
<td>Read resource specific permissions granted on a user account</td>
</tr>
<tr>
<td>e197c06f-ae7b-4398-b0a2-89f76ebca159</td>
<td>RiskPreventionProviders.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read your organization&#39;s risk prevention providers, on behalf of the signed-in user.</td>
<td>Read all identity risk prevention providers</td>
</tr>
<tr>
<td>2a7babba-9623-4109-bc9c-79728cf3bb4f</td>
<td>RiskPreventionProviders.ReadWrite.All</td>
<td>Security Administrator</td>
<td>Allows the app to read and write your organization&#39;s risk prevention providers, on behalf of the signed-in user.</td>
<td>Read and write all identity risk prevention providers</td>
</tr>
<tr>
<td>344a729c-0285-42c6-9014-f12b9b8d6129</td>
<td>RoleAssignmentSchedule.Read.Directory</td>
<td>Directory Readers</td>
<td>Allows the app to read the active role-based access control (RBAC) assignments for your company&#39;s directory, on behalf of the signed-in user. This includes reading directory role templates, and directory roles.</td>
<td>Read all active role assignments for your company&#39;s directory</td>
</tr>
<tr>
<td>8c026be3-8e26-4774-9372-8d5d6f21daff</td>
<td>RoleAssignmentSchedule.ReadWrite.Directory</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to read and manage the active role-based access control (RBAC) assignments for your company&#39;s directory, on behalf of the signed-in user. This includes managing active directory role membership, and reading directory role templates, directory roles and active memberships.</td>
<td>Read, update, and delete all active role assignments for your company&#39;s directory</td>
</tr>
<tr>
<td>f71cd05c-3fdb-4568-aef2-e1cf62ee20d4</td>
<td>RoleAssignmentSchedule.Remove.Directory</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to delete the active role-based access control (RBAC) assignments for your company&#39;s directory, on behalf of the signed-in user.</td>
<td>Delete all active role assignments for your company&#39;s directory</td>
</tr>
<tr>
<td>eb0788c2-6d4e-4658-8c9e-c0fb8053f03d</td>
<td>RoleEligibilitySchedule.Read.Directory</td>
<td>Directory Readers</td>
<td>Allows the app to read the eligible role-based access control (RBAC) assignments for your company&#39;s directory, on behalf of the signed-in user. This includes reading directory role templates, and directory roles.</td>
<td>Read all eligible role assignments for your company&#39;s directory</td>
</tr>
<tr>
<td>62ade113-f8e0-4bf9-a6ba-5acb31db32fd</td>
<td>RoleEligibilitySchedule.ReadWrite.Directory</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to read and manage the eligible role-based access control (RBAC) assignments for your company&#39;s directory, on behalf of the signed-in user. This includes managing eligible directory role membership, and reading directory role templates, directory roles and eligible memberships.</td>
<td>Read, update, and delete  all eligible role assignments for your company&#39;s directory</td>
</tr>
<tr>
<td>58ac4fa2-b484-4d6e-ba97-beee2a574220</td>
<td>RoleEligibilitySchedule.Remove.Directory</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to delete the eligible role-based access control (RBAC) assignments for your company&#39;s directory, on behalf of the signed-in user.</td>
<td>Delete all eligible role assignments for your company&#39;s directory</td>
</tr>
<tr>
<td>48fec646-b2ba-4019-8681-8eb31435aded</td>
<td>RoleManagement.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read the role-based access control (RBAC) settings for all RBAC providers, on behalf of the signed-in user.  This includes reading role definitions and role assignments.</td>
<td>Read role management data for all RBAC providers</td>
</tr>
<tr>
<td>9619b88a-8a25-48a7-9571-d23be0337a79</td>
<td>RoleManagement.Read.CloudPC</td>
<td>Windows 365 Administrator</td>
<td>Allows the app to read the Cloud PC role-based access control (RBAC) settings, on behalf of the signed-in user.�� This includes reading Cloud PC role definitions and role assignments.</td>
<td>Read Cloud PC RBAC settings</td>
</tr>
<tr>
<td>dd689728-6eb8-4deb-bd38-2924a935f3de</td>
<td>RoleManagement.Read.Defender</td>
<td>Security Reader</td>
<td>Allows the app to read the role-based access control (RBAC) settings for your company&#39;s directory, on behalf of the signed-in user. This includes reading M365 Defender role definitions and role assignments.</td>
<td>Read M365 Defender RBAC configuration</td>
</tr>
<tr>
<td>741c54c3-0c1e-44a1-818b-3f97ab4e8c83</td>
<td>RoleManagement.Read.Directory</td>
<td>Directory Readers</td>
<td>Allows the app to read the role-based access control (RBAC) settings for your company&#39;s directory, on behalf of the signed-in user.  This includes reading directory role templates, directory roles and memberships.</td>
<td>Read directory RBAC settings</td>
</tr>
<tr>
<td>3bc15058-7858-4141-b24f-ae43b4e80b52</td>
<td>RoleManagement.Read.Exchange</td>
<td>Exchange Recipient Administrator</td>
<td>Allows the app to read the role-based access control (RBAC) settings for your organization&#39;s Exchange Online service, on behalf of the signed-in user. This includes reading Exchange management role definitions, role groups, role group membership, role assignments, management scopes, and role assignment policies.</td>
<td>Read Exchange Online RBAC configuration</td>
</tr>
<tr>
<td>501d06f8-07b8-4f18-b5c6-c191a4af7a82</td>
<td>RoleManagement.ReadWrite.CloudPC</td>
<td>Permissions Management Administrator</td>
<td>Allows the app to read and manage the Cloud PC role-based access control (RBAC) settings, on behalf of the signed-in user. This includes reading and managing Cloud PC role definitions and role assignments.</td>
<td>Read and write Cloud PC RBAC settings</td>
</tr>
<tr>
<td>d8914f8f-9f64-4bd1-b4d3-f5a701ed8457</td>
<td>RoleManagement.ReadWrite.Defender</td>
<td>Security Reader</td>
<td>Allows the app to read the role-based access control (RBAC) settings for your company&#39;s directory, on behalf of the signed-in user. This includes reading M365 Defender role definitions and role assignments.</td>
<td>Read M365 Defender RBAC configuration</td>
</tr>
<tr>
<td>d01b97e9-cbc0-49fe-810a-750afd5527a3</td>
<td>RoleManagement.ReadWrite.Directory</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to read and manage the role-based access control (RBAC) settings for your company&#39;s directory, on behalf of the signed-in user. This includes instantiating directory roles and managing directory role membership, and reading directory role templates, directory roles and memberships.</td>
<td>Read and write directory RBAC settings</td>
</tr>
<tr>
<td>c1499fe0-52b1-4b22-bed2-7a244e0e879f</td>
<td>RoleManagement.ReadWrite.Exchange</td>
<td>Exchange Administrator</td>
<td>Allows the app to read and manage the role-based access control (RBAC) settings for your organization&#39;s Exchange Online service, on behalf of the signed-in user. This includes reading, creating, updating, and deleting Exchange management role definitions, role groups, role group membership, role assignments, management scopes, and role assignment policies.</td>
<td>Read and write Exchange Online RBAC configuration</td>
</tr>
<tr>
<td>cce71173-f76d-446e-97ff-efb2d82e11b1</td>
<td>RoleManagementAlert.Read.Directory</td>
<td>Security Reader</td>
<td>Allows the app to read the role-based access control (RBAC) alerts for your company&#39;s directory, on behalf of the signed-in user. This includes reading alert statuses, alert definitions, alert configurations and incidents that lead to an alert.</td>
<td>Read all alert data for your company&#39;s directory</td>
</tr>
<tr>
<td>435644c6-a5b1-40bf-8f52-fe8e5b53e19c</td>
<td>RoleManagementAlert.ReadWrite.Directory</td>
<td>Security Reader</td>
<td>Allows the app to read and manage the role-based access control (RBAC) alerts for your company&#39;s directory, on behalf of the signed-in user. This includes managing alert settings, initiating alert scans, dismissing alerts, remediating alert incidents, and reading alert statuses, alert definitions, alert configurations and incidents that lead to an alert.</td>
<td>Read all alert data, configure alerts, and take actions on all alerts for your company&#39;s directory</td>
</tr>
<tr>
<td>7e26fdff-9cb1-4e56-bede-211fe0e420e8</td>
<td>RoleManagementPolicy.Read.AzureADGroup</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to read policies in Privileged Identity Management for Groups, on behalf of the signed-in user.</td>
<td>Read all policies in PIM for Groups</td>
</tr>
<tr>
<td>3de2cdbe-0ff5-47d5-bdee-7f45b4749ead</td>
<td>RoleManagementPolicy.Read.Directory</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to read policies for privileged role-based access control (RBAC) assignments of your company&#39;s directory, on behalf of the signed-in user.</td>
<td>Read all policies for privileged role assignments of your company&#39;s directory</td>
</tr>
<tr>
<td>0da165c7-3f15-4236-b733-c0b0f6abe41d</td>
<td>RoleManagementPolicy.ReadWrite.AzureADGroup</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to read, update, and delete policies in Privileged Identity Management for Groups, on behalf of the signed-in user.</td>
<td>Read, update, and delete all policies in PIM for Groups</td>
</tr>
<tr>
<td>1ff1be21-34eb-448c-9ac9-ce1f506b2a68</td>
<td>RoleManagementPolicy.ReadWrite.Directory</td>
<td>Privileged Role Administrator</td>
<td>Allows the app to read, update, and delete policies for privileged role-based access control (RBAC) assignments of your company&#39;s directory, on behalf of the signed-in user.</td>
<td>Read, update, and delete all policies for privileged role assignments of your company&#39;s directory</td>
</tr>
<tr>
<td>fccf6dd8-5706-49fa-811f-69e2e1b585d0</td>
<td>Schedule.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read schedule, schedule groups, shifts and associated entities in the Teams or Shifts application on behalf of the signed-in user.</td>
<td>Read user schedule items</td>
</tr>
<tr>
<td>63f27281-c9d9-4f29-94dd-6942f7f1feb0</td>
<td>Schedule.ReadWrite.All</td>
<td>Teams Administrator</td>
<td>Allows the app to manage schedule, schedule groups, shifts and associated entities in the Teams or Shifts application on behalf of the signed-in user.</td>
<td>Read and write user schedule items</td>
</tr>
<tr>
<td>07919803-6073-4cd8-bc55-28077db0ee10</td>
<td>SchedulePermissions.ReadWrite.All</td>
<td>Teams Administrator</td>
<td>Allows the app to read/write schedule permissions for a specific role in Shifts application on behalf of the signed-in user.</td>
<td>Read/Write schedule permissions for a role.</td>
</tr>
<tr>
<td>7d307522-aa38-4cd0-bd60-90c6f0ac50bd</td>
<td>SearchConfiguration.Read.All</td>
<td>Search Administrator</td>
<td>Allows the app to read search configuration, on behalf of the signed-in user.</td>
<td>Read your organization&#39;s search configuration</td>
</tr>
<tr>
<td>b1a7d408-cab0-47d2-a2a5-a74a3733600d</td>
<td>SearchConfiguration.ReadWrite.All</td>
<td>Search Administrator</td>
<td>Allows the app to read and write search configuration, on behalf of the signed-in user.</td>
<td>Read and write your organization&#39;s search configuration</td>
</tr>
<tr>
<td>1638cddf-07a4-4de2-8645-69c96cacad73</td>
<td>SecurityActions.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read security actions, on behalf of the signed-in user.</td>
<td>Read your organization&#39;s security actions</td>
</tr>
<tr>
<td>dc38509c-b87d-4da0-bd92-6bec988bac4a</td>
<td>SecurityActions.ReadWrite.All</td>
<td>Security Operator</td>
<td>Allows the app to read or update security actions, on behalf of the signed-in user.</td>
<td>Read and update your organization&#39;s security actions</td>
</tr>
<tr>
<td>bc257fb8-46b4-4b15-8713-01e91bfbe4ea</td>
<td>SecurityAlert.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read all security alerts, on behalf of the signed-in user.</td>
<td>Read all security alerts</td>
</tr>
<tr>
<td>471f2a7f-2a42-4d45-a2bf-594d0838070d</td>
<td>SecurityAlert.ReadWrite.All</td>
<td>Security Operator</td>
<td>Allows the app to read and write to all security alerts, on behalf of the signed-in user.</td>
<td>Read and write to all security alerts</td>
</tr>
<tr>
<td>53e6783e-b127-4a35-ab3a-6a52d80a9077</td>
<td>SecurityAnalyzedMessage.Read.All</td>
<td>Security Reader</td>
<td>Read email metadata and security detection details on behalf of the signed in user.</td>
<td>Read metadata and detection details for emails in your organization</td>
</tr>
<tr>
<td>48eb8c83-6e58-46e7-a6d3-8805822f5940</td>
<td>SecurityAnalyzedMessage.ReadWrite.All</td>
<td>Security Reader</td>
<td>Read email metadata, security detection details, and execute remediation actions like deleting an email, on behalf of the signed in user.</td>
<td>Read metadata, detection details, and execute remediation actions on emails in your organization</td>
</tr>
<tr>
<td>64733abd-851e-478a-bffb-e47a14b18235</td>
<td>SecurityEvents.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read your organization�??s security events on behalf of the signed-in user.</td>
<td>Read your organization�??s security events</td>
</tr>
<tr>
<td>6aedf524-7e1c-45a7-bd76-ded8cab8d0fc</td>
<td>SecurityEvents.ReadWrite.All</td>
<td>Security Operator</td>
<td>Allows the app to read your organization�??s security events on behalf of the signed-in user. Also allows the app to update editable properties in security events on behalf of the signed-in user.</td>
<td>Read and update your organization�??s security events</td>
</tr>
<tr>
<td>a0d0da43-a6df-4416-b63d-99c79991aae8</td>
<td>SecurityIdentitiesHealth.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read all the identity security health issues of signed user</td>
<td>Read identity security health issues</td>
</tr>
<tr>
<td>53e51eec-2d9b-4990-97f3-c9aa5d5652c3</td>
<td>SecurityIdentitiesHealth.ReadWrite.All</td>
<td>Security Operator</td>
<td>Allows the app to read and write identity security health issues on behalf of the signed-in user.</td>
<td>Read and write identity security health issues</td>
</tr>
<tr>
<td>2c221239-7c5c-4b30-9355-d84663bfcd96</td>
<td>SecurityIdentitiesSensors.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read all the identity security sensors of signed user</td>
<td>Read identity security sensors</td>
</tr>
<tr>
<td>087c3ad9-c2ca-4b82-9885-d5e25ce9e183</td>
<td>SecurityIdentitiesSensors.ReadWrite.All</td>
<td>Security Operator</td>
<td>Allows the app to read and write identity security sensors on behalf of the signed-in user.</td>
<td>Read and write identity security sensors</td>
</tr>
<tr>
<td>c7d0a939-da1c-4aca-80fa-d0a6cd924801</td>
<td>SecurityIdentitiesUserActions.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read all the identity security available user actions of signed user</td>
<td>Read identity security available user actions</td>
</tr>
<tr>
<td>bf230e97-1957-4df6-b3f6-57f9029eacdf</td>
<td>SecurityIdentitiesUserActions.ReadWrite.All</td>
<td>Security Operator</td>
<td>Allows the app to read and write identity security available user actions on behalf of the signed-in user.</td>
<td>Read and perform identity security available user actions</td>
</tr>
<tr>
<td>b9abcc4f-94fc-4457-9141-d20ce80ec952</td>
<td>SecurityIncident.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read security incidents, on behalf of the signed-in user.</td>
<td>Read incidents</td>
</tr>
<tr>
<td>128ca929-1a19-45e6-a3b8-435ec44a36ba</td>
<td>SecurityIncident.ReadWrite.All</td>
<td>Security Operator</td>
<td>Allows the app to read and write security incidents, on behalf of the signed-in user.</td>
<td>Read and write to incidents</td>
</tr>
<tr>
<td>1fe7aa48-9373-4a47-8df3-168335e0f4c9</td>
<td>ServiceActivity-Exchange.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read all Exchange service activity, on behalf of the signed-in user.</td>
<td>Read all Exchange service activity</td>
</tr>
<tr>
<td>d74c75b1-d5a9-479d-902d-92f8f99182c1</td>
<td>ServiceActivity-Microsoft365Web.Read.All</td>
<td>Reports Reader</td>
<td>Allows the app to read all Microsoft 365 Web service activity, on behalf of the signed-in user.</td>
<td>Read all Microsoft 365 Web service activity</td>
</tr>
<tr>
<td>347e3c16-30f3-4ac7-9b52-fc3c053de9c9</td>
<td>ServiceActivity-OneDrive.Read.All</td>
<td>Reports Reader</td>
<td>Allows the app to read all One Drive service activity, on behalf of the signed-in user.</td>
<td>Read all One Drive service activity</td>
</tr>
<tr>
<td>404d76f0-e10e-460a-92be-ef19600c54d1</td>
<td>ServiceActivity-Teams.Read.All</td>
<td>Reports Reader</td>
<td>Allows the app to read all Teams service activity, on behalf of the signed-in user.</td>
<td>Read all Teams service activity</td>
</tr>
<tr>
<td>55896846-df78-47a7-aa94-8d3d4442ca7f</td>
<td>ServiceHealth.Read.All</td>
<td>Service Support Administrator</td>
<td>Allows the app to read your tenant&#39;s service health information on behalf of the signed-in user. Health information may include service issues or service health overviews.</td>
<td>Read service health</td>
</tr>
<tr>
<td>eda39fa6-f8cf-4c3c-a909-432c683e4c9b</td>
<td>ServiceMessage.Read.All</td>
<td>Message Center Reader</td>
<td>Allows the app to read your tenant&#39;s service announcement messages on behalf of the signed-in user. Messages may include information about new or changed features.</td>
<td>Read service announcement messages</td>
</tr>
<tr>
<td>636e1b0b-1cc2-4b1c-9aa9-4eeed9b9761b</td>
<td>ServiceMessageViewpoint.Write</td>
<td>Service Support Administrator</td>
<td>Allows the app to update service announcement messages&#39; user status on behalf of the signed-in user. The message status can be marked as read, archive, or favorite.</td>
<td>Update user status on service announcement messages</td>
</tr>
<tr>
<td>9f9ce928-e038-4e3b-8faf-7b59049a8ddc</td>
<td>ServicePrincipalEndpoint.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read service principal endpoints</td>
<td>Read service principal endpoints</td>
</tr>
<tr>
<td>7297d82c-9546-4aed-91df-3d4f0a9b3ff0</td>
<td>ServicePrincipalEndpoint.ReadWrite.All</td>
<td>Application Administrator</td>
<td>Allows the app to update service principal endpoints</td>
<td>Read and update service principal endpoints</td>
</tr>
<tr>
<td>2ef70e10-5bfd-4ede-a5f6-67720500b258</td>
<td>SharePointTenantSettings.Read.All</td>
<td>SharePoint Administrator</td>
<td>Allows the application to read the tenant-level settings in SharePoint and OneDrive on behalf of the signed-in user.</td>
<td>Read SharePoint and OneDrive tenant settings</td>
</tr>
<tr>
<td>aa07f155-3612-49b8-a147-6c590df35536</td>
<td>SharePointTenantSettings.ReadWrite.All</td>
<td>SharePoint Administrator</td>
<td>Allows the application to read and change the tenant-level settings of SharePoint and OneDrive on behalf of the signed-in user.</td>
<td>Read and change SharePoint and OneDrive tenant settings</td>
</tr>
<tr>
<td>5a54b8b3-347c-476d-8f8e-42d5c7424d29</td>
<td>Sites.FullControl.All</td>
<td>SharePoint Administrator</td>
<td>Allows the application to have full control of all site collections on behalf of the signed-in user.</td>
<td>Have full control of all site collections</td>
</tr>
<tr>
<td>9b4aa4b1-aaf3-41b7-b743-698b27e77ff6</td>
<td>SpiffeTrustDomain.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read your organization&#39;s SPIFFE trust domains and child resources on behalf of the user.</td>
<td>Read SPIFFE trust domains and child resources</td>
</tr>
<tr>
<td>8ba47079-8c47-4bfe-b2ce-13f28ef37247</td>
<td>SpiffeTrustDomain.ReadWrite.All</td>
<td>Global Administrator</td>
<td>Allows the app to read and write your organization&#39;s SPIFFE trust domains and child resources on behalf of the user.</td>
<td>Read and write SPIFFE trust domains and child resources</td>
</tr>
<tr>
<td>9c3af74c-fd0f-4db4-b17a-71939e2a9d77</td>
<td>SubjectRightsRequest.Read.All</td>
<td>Message Center Privacy Reader</td>
<td>Allows the app to read subject rights requests on behalf of the signed-in user</td>
<td>Read subject rights requests</td>
</tr>
<tr>
<td>2b8fcc74-bce1-4ae3-a0e8-60c53739299d</td>
<td>SubjectRightsRequest.ReadWrite.All</td>
<td>User Administrator</td>
<td>Allows the app to read and write subject rights requests on behalf of the signed-in user</td>
<td>Read and write subject rights requests</td>
</tr>
<tr>
<td>5f88184c-80bb-4d52-9ff2-757288b2e9b7</td>
<td>Subscription.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read all webhook subscriptions on behalf of the signed-in user.</td>
<td>Read all webhook subscriptions </td>
</tr>
<tr>
<td>7aa02aeb-824f-4fbe-a3f7-611f751f5b55</td>
<td>Synchronization.Read.All</td>
<td>Hybrid Identity Administrator</td>
<td>Allows the app to read Azure AD synchronization information, on behalf of the signed-in user.</td>
<td>Read all Azure AD synchronization data</td>
</tr>
<tr>
<td>7bb27fa3-ea8f-4d67-a916-87715b6188bd</td>
<td>Synchronization.ReadWrite.All</td>
<td>Hybrid Identity Administrator</td>
<td>Allows the app to configure the Azure AD synchronization service, on behalf of the signed-in user.</td>
<td>Read and write all Azure AD synchronization data</td>
</tr>
<tr>
<td>1a2e7420-4e92-4d2b-94cb-fb2952e9ddf7</td>
<td>SynchronizationData-User.Upload</td>
<td>Hybrid Identity Administrator</td>
<td>Allows the app to upload bulk user data to the identity synchronization service, on behalf of the signed-in user.</td>
<td>Upload user data to the identity synchronization service</td>
</tr>
<tr>
<td>2497278c-d82d-46a2-b1ce-39d4cdde5570</td>
<td>TeamMember.Read.All</td>
<td>Teams Administrator</td>
<td>Read the members of teams, on behalf of the signed-in user.</td>
<td>Read the members of teams</td>
</tr>
<tr>
<td>4a06efd2-f825-4e34-813e-82a57b03d1ee</td>
<td>TeamMember.ReadWrite.All</td>
<td>Teams Administrator</td>
<td>Add and remove members from teams, on behalf of the signed-in user. Also allows changing a member&#39;s role, for example from owner to non-owner.</td>
<td>Add and remove members from teams</td>
</tr>
<tr>
<td>2104a4db-3a2f-4ea0-9dba-143d457dc666</td>
<td>TeamMember.ReadWriteNonOwnerRole.All</td>
<td>Groups Administrator</td>
<td>Add and remove members from all teams, on behalf of the signed-in user. Does not allow adding or removing a member with the owner role. Additionally, does not allow the app to elevate an existing member to the owner role.</td>
<td>Add and remove members with non-owner role for all teams</td>
</tr>
<tr>
<td>d1ba22c6-3f02-4c91-addb-bc3399bcca88</td>
<td>TeamsAppInstallation.ManageSelectedForChat</td>
<td>Teams Administrator</td>
<td>Allows the app to read, install, upgrade, and uninstall selected Teams apps in chats the signed-in user can access. Gives the ability to manage permission grants for accessing those specific chats&#39; data.</td>
<td>Manage installation and permission grants of selected Teams apps in chats</td>
</tr>
<tr>
<td>c67b2d7e-6b80-4218-938a-05e73058e42d</td>
<td>TeamsAppInstallation.ManageSelectedForTeam</td>
<td>Teams Administrator</td>
<td>Allows the app to read, install, upgrade, and uninstall Teams apps in teams the signed-in user can access. Gives the ability to manage permission grants for accessing those specific teams&#39; data.</td>
<td>Manage installation and permission grants of selected Teams apps in teams</td>
</tr>
<tr>
<td>830c2bd9-c335-4caf-bf83-c07fa8a23ef1</td>
<td>TeamsAppInstallation.ManageSelectedForUser</td>
<td>Teams Administrator</td>
<td>Allows the app to read, install, upgrade, and uninstall seleected Teams apps in user accounts, on behalf of the signed-in user. Gives the ability to manage permission grants for accessing those specific users&#39; data.</td>
<td>Manage installation and permission grants of selected Teams apps in users&#39; personal scope</td>
</tr>
<tr>
<td>5248dcb1-f83b-4ec3-9f4d-a4428a961a72</td>
<td>TeamsAppInstallation.ReadForTeam</td>
<td>Global Reader</td>
<td>Allows the app to read the Teams apps that are installed in teams the signed-in user can access. Does not give the ability to read application-specific settings.</td>
<td>Read installed Teams apps in teams</td>
</tr>
<tr>
<td>0f3420c2-c6ec-46de-ab72-fd51267087d5</td>
<td>TeamsAppInstallation.ReadSelectedForChat</td>
<td>Reports Reader</td>
<td>Allows the app to read the selected Teams apps that are installed in chats the signed-in user can access. Does not give the ability to read application-specific settings.</td>
<td>Read selected installed Teams apps in chats</td>
</tr>
<tr>
<td>b55df1c0-db20-435b-aef2-afe6ed487e16</td>
<td>TeamsAppInstallation.ReadSelectedForTeam</td>
<td>Reports Reader</td>
<td>Allows the app to read the selected Teams apps that are installed in teams the signed-in user can access. Does not give the ability to read application-specific settings.</td>
<td>Read selected installed Teams apps in teams</td>
</tr>
<tr>
<td>fe2e4e1d-101f-4fb2-9cb1-9d6659db45d4</td>
<td>TeamsAppInstallation.ReadSelectedForUser</td>
<td>Reports Reader</td>
<td>Allows the app to read the selected Teams apps that are installed for the signed-in user. Does not give the ability to read application-specific settings.</td>
<td>Read user&#39;s selected installed Teams apps</td>
</tr>
<tr>
<td>e1408a66-8f82-451b-a2f3-3c3e38f7413f</td>
<td>TeamsAppInstallation.ReadWriteAndConsentForChat</td>
<td>Teams Administrator</td>
<td>Allows the app to read, install, upgrade, and uninstall Teams apps in chats the signed-in user can access. Gives the ability to manage permission grants for accessing those specific chats&#39; data.</td>
<td>Manage installed Teams apps in chats</td>
</tr>
<tr>
<td>946349d5-2a9d-4535-abc0-7beeacaedd1d</td>
<td>TeamsAppInstallation.ReadWriteAndConsentForTeam</td>
<td>Teams Administrator</td>
<td>Allows the app to read, install, upgrade, and uninstall Teams apps in teams the signed-in user can access. Gives the ability to manage permission grants for accessing those specific teams&#39; data.</td>
<td>Manage installed Teams apps in teams</td>
</tr>
<tr>
<td>2da62c49-dfbd-40df-ba16-fef3529d391c</td>
<td>TeamsAppInstallation.ReadWriteAndConsentForUser</td>
<td>Teams Administrator</td>
<td>Allows the app to read, install, upgrade, and uninstall Teams apps in user accounts, on behalf of the signed-in user. Gives the ability to manage permission grants for accessing those specific users&#39; data.</td>
<td>Manage installation and permission grants of Teams apps in users&#39; personal scope</td>
</tr>
<tr>
<td>a0e0e18b-8fb2-458f-8130-da2d7cab9c75</td>
<td>TeamsAppInstallation.ReadWriteAndConsentSelfForChat</td>
<td>Teams Administrator</td>
<td>Allows a Teams app to read, install, upgrade, and uninstall itself in chats the signed-in user can access, and manage its permission grants for accessing those specific chats&#39; data.</td>
<td>Allow the Teams app to manage itself and its permission grants in chats</td>
</tr>
<tr>
<td>4a6bbf29-a0e1-4a4d-a7d1-cef17f772975</td>
<td>TeamsAppInstallation.ReadWriteAndConsentSelfForTeam</td>
<td>Teams Administrator</td>
<td>Allows a Teams app to read, install, upgrade, and uninstall itself in teams the signed-in user can access, and manage its permission grants for accessing those specific teams&#39; data.</td>
<td>Allow the Teams app to manage itself and its permission grants in teams</td>
</tr>
<tr>
<td>7a349935-c54d-44ab-ab66-1b460d315be7</td>
<td>TeamsAppInstallation.ReadWriteAndConsentSelfForUser</td>
<td>User Administrator</td>
<td>Allows a Teams app to read, install, upgrade, and uninstall itself in user accounts, and manage its permission grants for accessing those specific users&#39; data, on behalf of the signed-in user.</td>
<td>Allow the Teams app to manage itself and its permission grants in user accounts</td>
</tr>
<tr>
<td>aa85bf13-d771-4d5d-a9e6-bca04ce44edf</td>
<td>TeamsAppInstallation.ReadWriteForChat</td>
<td>Teams Administrator</td>
<td>Allows the app to read, install, upgrade, and uninstall Teams apps in chats the signed-in user can access. Does not give the ability to read application-specific settings.</td>
<td>Manage installed Teams apps in chats</td>
</tr>
<tr>
<td>2e25a044-2580-450d-8859-42eeb6e996c0</td>
<td>TeamsAppInstallation.ReadWriteForTeam</td>
<td>Teams Administrator</td>
<td>Allows the app to read, install, upgrade, and uninstall Teams apps in teams the signed-in user can access. Does not give the ability to read application-specific settings.</td>
<td>Manage installed Teams apps in teams</td>
</tr>
<tr>
<td>093f8818-d05f-49b8-95bc-9d2a73e9a43c</td>
<td>TeamsAppInstallation.ReadWriteForUser</td>
<td>Teams Administrator</td>
<td>Allows the app to read, install, upgrade, and uninstall Teams apps installed for the signed-in user. Does not give the ability to read application-specific settings.</td>
<td>Manage user&#39;s installed Teams apps</td>
</tr>
<tr>
<td>690aa3b6-4b71-41c2-a990-77a8c4768d2b</td>
<td>TeamsAppInstallation.ReadWriteSelectedForChat</td>
<td>Teams Administrator</td>
<td>Allows the app to read, install, upgrade, and uninstall selected Teams apps in chats the signed-in user can access. Does not give the ability to read application-specific settings.</td>
<td>Manage selected Teams apps installed in chats</td>
</tr>
<tr>
<td>9131c833-9a49-4c54-b38f-615ecfc4fc69</td>
<td>TeamsAppInstallation.ReadWriteSelectedForTeam</td>
<td>Teams Administrator</td>
<td>Allows the app to read, install, upgrade, and uninstall selected Teams apps in teams the signed-in user can access. Does not give the ability to read application-specific settings.</td>
<td>Manage selected Teams apps installed in teams</td>
</tr>
<tr>
<td>ea819e27-c92a-4118-b83b-4540b125d744</td>
<td>TeamsAppInstallation.ReadWriteSelectedForUser</td>
<td>User Administrator</td>
<td>Allows the app to read, install, upgrade, and uninstall selected Teams apps installed for the signed in user. Does not give the ability to read application-specific settings.</td>
<td>Manage selected Teams apps installed for a user</td>
</tr>
<tr>
<td>0ce33576-30e8-43b7-99e5-62f8569a4002</td>
<td>TeamsAppInstallation.ReadWriteSelfForChat</td>
<td>Teams Administrator</td>
<td>Allows a Teams app to read, install, upgrade, and uninstall itself in chats the signed-in user can access.</td>
<td>Allow the Teams app to manage itself in chats</td>
</tr>
<tr>
<td>0f4595f7-64b1-4e13-81bc-11a249df07a9</td>
<td>TeamsAppInstallation.ReadWriteSelfForTeam</td>
<td>Teams Administrator</td>
<td>Allows a Teams app to read, install, upgrade, and uninstall itself to teams the signed-in user can access.</td>
<td>Allow the app to manage itself in teams</td>
</tr>
<tr>
<td>48638b3c-ad68-4383-8ac4-e6880ee6ca57</td>
<td>TeamSettings.Read.All</td>
<td>Teams Administrator</td>
<td>Read all teams&#39; settings, on behalf of the signed-in user.</td>
<td>Read teams&#39; settings</td>
</tr>
<tr>
<td>39d65650-9d3e-4223-80db-a335590d027e</td>
<td>TeamSettings.ReadWrite.All</td>
<td>Teams Administrator</td>
<td>Read and change all teams&#39; settings, on behalf of the signed-in user.</td>
<td>Read and change teams&#39; settings</td>
</tr>
<tr>
<td>6997c35c-a586-440c-8a0b-4ffe5d118dc0</td>
<td>TeamsPolicyUserAssign.ReadWrite.All</td>
<td>Teams Administrator</td>
<td>Allow the app to read or write/update the policy assignment and unassigment for Teams users for all policy type categories.</td>
<td>Read and Write Teams policy user assignment and unassigment for all policy types.</td>
</tr>
<tr>
<td>ea2cbd09-253c-4f69-a0e6-07383c5f07cc</td>
<td>TeamsResourceAccount.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read your tenant&#39;s resource accounts on behalf of the signed-in admin user.</td>
<td>Read Teams resource accounts</td>
</tr>
<tr>
<td>a9ff19c2-f369-4a95-9a25-ba9d460efc8e</td>
<td>TeamsTab.Create</td>
<td>Teams Administrator</td>
<td>Allows the app to create tabs in any team in Microsoft Teams, on behalf of the signed-in user. This does not grant the ability to read, modify or delete tabs after they are created, or give access to the content inside the tabs.</td>
<td>Create tabs in Microsoft Teams.</td>
</tr>
<tr>
<td>59dacb05-e88d-4c13-a684-59f1afc8cc98</td>
<td>TeamsTab.Read.All</td>
<td>Teams Administrator</td>
<td>Read the names and settings of tabs inside any team in Microsoft Teams, on behalf of the signed-in user. This does not give access to the content inside the tabs.</td>
<td>Read tabs in Microsoft Teams.</td>
</tr>
<tr>
<td>b98bfd41-87c6-45cc-b104-e2de4f0dafb9</td>
<td>TeamsTab.ReadWrite.All</td>
<td>Teams Administrator</td>
<td>Read and write tabs in any team in Microsoft Teams, on behalf of the signed-in user. This does not give access to the content inside the tabs.</td>
<td>Read and write tabs in Microsoft Teams.</td>
</tr>
<tr>
<td>ee928332-e9c2-4747-b4a0-f8c164b68de6</td>
<td>TeamsTab.ReadWriteForChat</td>
<td>Teams Administrator</td>
<td>Allows a Teams app to read, install, upgrade, and uninstall all tabs in chats the signed-in user can access.</td>
<td>Allow the Teams app to manage all tabs in chats</td>
</tr>
<tr>
<td>c975dd04-a06e-4fbb-9704-62daad77bb49</td>
<td>TeamsTab.ReadWriteForTeam</td>
<td>Teams Administrator</td>
<td>Allows a Teams app to read, install, upgrade, and uninstall all tabs to teams the signed-in user can access.</td>
<td>Allow the Teams app to manage all tabs in teams</td>
</tr>
<tr>
<td>0c219d04-3abf-47f7-912d-5cca239e90e6</td>
<td>TeamsTab.ReadWriteSelfForChat</td>
<td>Teams Administrator</td>
<td>Allows a Teams app to read, install, upgrade, and uninstall its own tabs in chats the signed-in user can access.</td>
<td>Allow the Teams app to manage only its own tabs in chats</td>
</tr>
<tr>
<td>f266662f-120a-4314-b26a-99b08617c7ef</td>
<td>TeamsTab.ReadWriteSelfForTeam</td>
<td>Teams Administrator</td>
<td>Allows a Teams app to read, install, upgrade, and uninstall its own tabs to teams the signed-in user can access.</td>
<td>Allow the Teams app to manage only its own tabs in teams</td>
</tr>
<tr>
<td>1bc6eab1-058d-4557-b011-d4c41cec88b7</td>
<td>TeamsTelephoneNumber.Read.All</td>
<td>Teams Telephony Administrator</td>
<td>Allows the app to read your tenant&#39;s acquired telephone number details on behalf of the signed-in admin user. Acquired telephone numbers may include attributes related to assigned object, emergency location, network site, etc.</td>
<td>Read Tenant-Acquired Telephone Number Details</td>
</tr>
<tr>
<td>424b07a8-1209-4d17-9fe4-9018a93a1024</td>
<td>TeamsTelephoneNumber.ReadWrite.All</td>
<td>Teams Telephony Administrator</td>
<td>Allows the app to read and modify your tenant&#39;s acquired telephone number details on behalf of the signed-in admin user. Acquired telephone numbers may include attributes related to assigned object, emergency location, network site, etc.</td>
<td>Read and Modify Tenant-Acquired Telephone Number Details</td>
</tr>
<tr>
<td>5c469ce4-dab5-4afd-b9de-14f1ba4004a7</td>
<td>TeamsUserConfiguration.Read.All</td>
<td>Teams Administrator</td>
<td>Allows the app to read your tenant&#39;s user configurations on behalf of the signed-in admin user. User configuration may include attributes related to user, such as telephone number, assigned policies, etc.</td>
<td>Read Teams user configurations</td>
</tr>
<tr>
<td>594f4bb6-c083-4cf9-8aa8-213823bdf351</td>
<td>Teamwork.Read.All</td>
<td>Teams Administrator</td>
<td>Allows the app to read the teamwork settings of the organization, on behalf of the signed-in user.</td>
<td>Read organizational teamwork settings</td>
</tr>
<tr>
<td>87c556f0-2bd9-4eed-bd74-5dd8af6eaf7e</td>
<td>TeamworkAppSettings.ReadWrite.All</td>
<td>Global Reader</td>
<td>Allows the app to read and write the Teams app settings on behalf of the signed-in user.</td>
<td>Read and write Teams app settings</td>
</tr>
<tr>
<td>b659488b-9d28-4208-b2be-1c6652b3c970</td>
<td>TeamworkDevice.Read.All</td>
<td>Teams Devices Administrator</td>
<td>Allow the app to read the management data for Teams devices on behalf of the signed-in user.</td>
<td>Read Teams devices</td>
</tr>
<tr>
<td>ddd97ecb-5c31-43db-a235-0ee20e635c40</td>
<td>TeamworkDevice.ReadWrite.All</td>
<td>Teams Devices Administrator</td>
<td>Allow the app to read and write the management data for Teams devices on behalf of the signed-in user.</td>
<td>Read and write Teams devices</td>
</tr>
<tr>
<td>57587d0b-8399-45be-b207-8050cec54575</td>
<td>TeamworkTag.Read</td>
<td>Directory Readers</td>
<td>Allows the app to read tags in Teams, on behalf of the signed-in user.</td>
<td>Read tags in Teams</td>
</tr>
<tr>
<td>539dabd7-b5b6-4117-b164-d60cd15a8671</td>
<td>TeamworkTag.ReadWrite</td>
<td>Teams Administrator</td>
<td>Allows the app to read and write tags in Teams, on behalf of the signed-in user.</td>
<td>Read and write tags in Teams</td>
</tr>
<tr>
<td>b4d26916-07e0-4daf-9096-9f6d9174aa96</td>
<td>TeamworkUserInteraction.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read all of the possible Teams interactions between the signed-in user and other users</td>
<td>Read all of the possible Teams interactions between the user and other users</td>
</tr>
<tr>
<td>297f747b-0005-475b-8fef-c890f5152b38</td>
<td>TermStore.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read the term store data that the signed-in user has access to. This includes all sets, groups and terms in the term store.</td>
<td>Read term store data</td>
</tr>
<tr>
<td>6c37c71d-f50f-4bff-8fd3-8a41da390140</td>
<td>TermStore.ReadWrite.All</td>
<td>Knowledge Administrator</td>
<td>Allows the app to read or modify data that the signed-in user has access to.��This includes all sets, groups and terms in the term store.</td>
<td>Read and write term store data</td>
</tr>
<tr>
<td>cac97e40-6730-457d-ad8d-4852fddab7ad</td>
<td>ThreatAssessment.ReadWrite.All</td>
<td>Security Reader</td>
<td>Allows an app to read your organization&#39;s threat assessment requests on behalf of the signed-in user. Also allows the app to create new requests to assess threats received by your organization on behalf of the signed-in user.</td>
<td>Read and write threat assessment requests</td>
</tr>
<tr>
<td>b152eca8-ea73-4a48-8c98-1a6742673d99</td>
<td>ThreatHunting.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to run hunting queries, on behalf of the signed-in user.</td>
<td>Run hunting queries</td>
</tr>
<tr>
<td>9cc427b4-2004-41c5-aa22-757b755e9796</td>
<td>ThreatIndicators.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read all the indicators for your organization, on behalf of the signed-in user.</td>
<td>Read all threat indicators</td>
</tr>
<tr>
<td>91e7d36d-022a-490f-a748-f8e011357b42</td>
<td>ThreatIndicators.ReadWrite.OwnedBy</td>
<td>Security Operator</td>
<td>Allows the app to create threat indicators, and fully manage those threat indicators (read, update and delete), on behalf of the signed-in user. ��It cannot update any threat indicators it does not own.</td>
<td>Manage threat indicators this app creates or owns</td>
</tr>
<tr>
<td>f266d9c0-ccb9-4fb8-a228-01ac0d8d6627</td>
<td>ThreatIntelligence.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read threat intelligence information, such as indicators, observations, and articles, on behalf of the signed-in user.</td>
<td>Read all threat intelligence information</td>
</tr>
<tr>
<td>7083913a-4966-44b6-9886-c5822a5fd910</td>
<td>ThreatSubmission.Read.All</td>
<td>Security Reader</td>
<td>Allows the app to read your organization&#39;s threat submissions and threat submission policies on behalf of the signed-in user.</td>
<td>Read all threat submissions</td>
</tr>
<tr>
<td>8458e264-4eb9-4922-abe9-768d58f13c7f</td>
<td>ThreatSubmission.ReadWrite.All</td>
<td>Security Operator</td>
<td>Allows the app to read your organization&#39;s threat submissions and threat submission policies on behalf of the signed-in user. Also allows the app to create new threat submissions on behalf of the signed-in user.</td>
<td>Read and write all threat submissions</td>
</tr>
<tr>
<td>059e5840-5353-4c68-b1da-666a033fc5e8</td>
<td>ThreatSubmissionPolicy.ReadWrite.All</td>
<td>Security Administrator</td>
<td>Allows the app to read your organization&#39;s threat submission policies on behalf of the signed-in user. Also allows the app to create new threat submission policies on behalf of the signed-in user.</td>
<td>Read and write all threat submission policies</td>
</tr>
<tr>
<td>79c4c76f-409a-4f98-884d-e2c09291ec26</td>
<td>Topic.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read topics data on behalf of the signed-in user.</td>
<td>Read topic items</td>
</tr>
<tr>
<td>7ad34336-f5b1-44ce-8682-31d7dfcd9ab9</td>
<td>TrustFrameworkKeySet.Read.All</td>
<td>B2C IEF Keyset Administrator</td>
<td>Allows the app to read trust framework key set properties on behalf of the signed-in user.</td>
<td>Read trust framework key sets</td>
</tr>
<tr>
<td>39244520-1e7d-4b4a-aee0-57c65826e427</td>
<td>TrustFrameworkKeySet.ReadWrite.All</td>
<td>B2C IEF Keyset Administrator</td>
<td>Allows the app to read and write trust framework key set properties on behalf of the signed-in user.</td>
<td>Read and write trust framework key sets</td>
</tr>
<tr>
<td>73e75199-7c3e-41bb-9357-167164dbb415</td>
<td>UnifiedGroupMember.Read.AsGuest</td>
<td>Directory Readers</td>
<td>Allows the app to read basic unified group properties, memberships and owners of the group the signed-in guest is a member of.</td>
<td>Read unified group memberships as guest</td>
</tr>
<tr>
<td>550e695c-7511-40f4-ac79-e8fb9c82552d</td>
<td>User-ConvertToInternal.ReadWrite.All</td>
<td>User Administrator</td>
<td>Allow the app to convert an external user to an internal member user, on behalf of signed-in user.</td>
<td>Convert an external user to internal memeber user</td>
</tr>
<tr>
<td>ed8d2a04-0374-41f1-aefe-da8ac87ccc87</td>
<td>User-LifeCycleInfo.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read the lifecycle information like employeeLeaveDateTime of users in your organization, on behalf of the signed-in user.</td>
<td>Read all users&#39; lifecycle information</td>
</tr>
<tr>
<td>7ee7473e-bd4b-4c9f-987c-bd58481f5fa2</td>
<td>User-LifeCycleInfo.ReadWrite.All</td>
<td>User Administrator</td>
<td>Allows the app to read and write the lifecycle information like employeeLeaveDateTime of users in your organization, on behalf of the signed-in user.</td>
<td>Read and write all users&#39; lifecycle information</td>
</tr>
<tr>
<td>6166886a-9576-433b-8544-658177bdef1d</td>
<td>User-Mail.ReadWrite.All</td>
<td>User Administrator</td>
<td>Allows the app to read and write secondary mail addresses for all users, on behalf of the signed-in user.</td>
<td>Read and write secondary mail addresses for users</td>
</tr>
<tr>
<td>56760768-b641-451f-8906-e1b8ab31bca7</td>
<td>User-PasswordProfile.ReadWrite.All</td>
<td>Helpdesk Administrator</td>
<td>Allows the app to read and write password profiles and reset passwords for all users, on behalf of the signed-in user.</td>
<td>Read and write password profiles and reset user passwords</td>
</tr>
<tr>
<td>e29d5979-5b06-4a7f-ae24-6a9348d2e1ff</td>
<td>User-Phone.ReadWrite.All</td>
<td>User Administrator</td>
<td>Allows the app to read and write the mobile phone and business phones for all users, on behalf of the signed-in user.</td>
<td>Read and write user mobile phone and business phones</td>
</tr>
<tr>
<td>4bb440cd-2cf2-4f90-8004-aa2acd2537c5</td>
<td>User.DeleteRestore.All</td>
<td>User Administrator</td>
<td>Allows the app to delete and restore all users, on behalf of the signed-in user.</td>
<td>Delete and restore users</td>
</tr>
<tr>
<td>f92e74e7-2563-467f-9dd0-902688cb5863</td>
<td>User.EnableDisableAccount.All</td>
<td>User Administrator</td>
<td>Allows the app to enable and disable users&#39; accounts, on behalf of the signed-in user.</td>
<td>Enable and disable user accounts</td>
</tr>
<tr>
<td>405a51b5-8d8d-430b-9842-8be4b0e9f324</td>
<td>User.Export.All</td>
<td>Global Reader</td>
<td>Allows the app to export data (e.g. customer content or system-generated logs), associated with any user in your company, when the app is used by a privileged user (e.g. a Company Administrator).</td>
<td>Export user&#39;s data</td>
</tr>
<tr>
<td>63dd7cd9-b489-4adf-a28c-ac38b9a0f962</td>
<td>User.Invite.All</td>
<td>Guest Inviter</td>
<td>Allows the app to invite guest users to the organization, on behalf of the signed-in user.</td>
<td>Invite guest users to the organization</td>
</tr>
<tr>
<td>637d7bec-b31e-4deb-acc9-24275642a2c9</td>
<td>User.ManageIdentities.All</td>
<td>User Administrator</td>
<td>Allows the app to read, update and delete identities that are associated with a user&#39;s account that the signed-in user has access to. This controls the identities users can sign-in with.</td>
<td>Manage  user identities</td>
</tr>
<tr>
<td>a154be20-db9c-4678-8ab7-66f6cc099a59</td>
<td>User.Read.All</td>
<td>Directory Readers</td>
<td>Allows the app to read the full set of profile properties, reports, and managers of other users in your organization, on behalf of the signed-in user.</td>
<td>Read all users&#39; full profiles</td>
</tr>
<tr>
<td>204e0828-b5ca-4ad8-b9f3-f32a958e7cc4</td>
<td>User.ReadWrite.All</td>
<td>User Administrator</td>
<td>Allows the app to read and write the full set of profile properties, reports, and managers of other users in your organization, on behalf of the signed-in user.</td>
<td>Read and write all users&#39; full profiles</td>
</tr>
<tr>
<td>fc30e98b-8810-4501-81f5-c20a3196387b</td>
<td>User.RevokeSessions.All</td>
<td>Helpdesk Administrator</td>
<td>Allow the app to revoke all sign in sessions for a user, on behalf of a signed-in user.</td>
<td>Revoke all sign in sessions for a user</td>
</tr>
<tr>
<td>1f6b61c5-2f65-4135-9c9f-31c0f8d32b52</td>
<td>UserAuthenticationMethod.Read</td>
<td>Reports Reader</td>
<td>Allows the app to read the signed-in user&#39;s authentication methods, including phone numbers and Authenticator app settings. This does not allow the app to see secret information like the signed-in user&#39;s passwords, or to sign-in  or otherwise use the signed-in user&#39;s authentication methods.</td>
<td>Read user authentication methods.</td>
</tr>
<tr>
<td>aec28ec7-4d02-4e8c-b864-50163aea77eb</td>
<td>UserAuthenticationMethod.Read.All</td>
<td>Helpdesk Administrator</td>
<td>Allows the app to read authentication methods of all users in your organization that the signed-in user has access to. Authentication methods include things like a user�??s phone numbers and Authenticator app settings. This does not allow the app to see secret information like passwords, or to sign-in or otherwise use the authentication methods.</td>
<td>Read all users&#39; authentication methods</td>
</tr>
<tr>
<td>48971fc1-70d7-4245-af77-0beb29b53ee2</td>
<td>UserAuthenticationMethod.ReadWrite</td>
<td>User Administrator</td>
<td>Allows the app to read and write the signed-in user&#39;s authentication methods, including phone numbers and Authenticator app settings.                       This does not allow the app to see secret information like the signed-in user&#39;s passwords, or                      to sign-in or otherwise use the signed-in user&#39;s authentication methods.  </td>
<td>Read and write user authentication methods</td>
</tr>
<tr>
<td>b7887744-6746-4312-813d-72daeaee7e2d</td>
<td>UserAuthenticationMethod.ReadWrite.All</td>
<td>Authentication Administrator</td>
<td> Allows the app to read and write authentication methods of all users in your organization that the signed-in user has access to.                       Authentication methods include things like a user�??s phone numbers and Authenticator app settings. This                      does not allow the app to see secret information like passwords, or to sign-in or otherwise use the authentication methods.</td>
<td>Read and write all users&#39; authentication methods.</td>
</tr>
<tr>
<td>14195339-1fe4-48a7-a0d3-a39eb9fd8958</td>
<td>UserAuthMethod-Passkey.Read.All</td>
<td>Helpdesk Administrator</td>
<td>Allows the app to read passkey authentication methods of all users in your organization that the signed-in user has access to. This does not allow the app to see secret information like passwords, or to sign-in or otherwise use the authentication methods.</td>
<td>Read all users&#39; passkey authentication methods</td>
</tr>
<tr>
<td>64930478-d0ea-4671-ad72-fe0d9821df09</td>
<td>UserAuthMethod-Passkey.ReadWrite.All</td>
<td>User Administrator</td>
<td>Allows the app to read and write passkey authentication methods of all users in your organization that the signed-in user has access to. This does not allow the app to see secret information like passwords, or to sign-in or otherwise use the authentication methods.</td>
<td>Read and write all users&#39; passkey methods.</td>
</tr>
<tr>
<td>834bcc1c-762f-41b0-bb91-1cdc323ee4bf</td>
<td>UserTeamwork.Read</td>
<td>User</td>
<td>Allows the app to read the teamwork settings of the signed-in user.</td>
<td>Read user teamwork settings</td>
</tr>
<tr>
<td>27470298-d3b8-4b9c-aad4-6334312a3eac</td>
<td>VirtualAppointment.Read</td>
<td>User Administrator</td>
<td>Allows an application to read virtual appointments for the signed-in user. Only an organizer or participant user can read their virtual appointments.�?��</td>
<td>Read a user&#39;s virtual appointments</td>
</tr>
<tr>
<td>2ccc2926-a528-4b17-b8bb-860eed29d64c</td>
<td>VirtualAppointment.ReadWrite</td>
<td>Teams Administrator</td>
<td>Allows an application to read and write virtual appointments for the signed-in user. Only an organizer or participant user can read and write their virtual appointments.�?�</td>
<td>Read and write a user&#39;s virtual appointments�?��</td>
</tr>
<tr>
<td>20d02fff-a0ef-49e7-a46e-019d4a6523b7</td>
<td>VirtualAppointmentNotification.Send</td>
<td>User</td>
<td>Allows an application to send notifications for virtual appointments for the signed-in user.</td>
<td>Send notification regarding virtual appointments for the signed-in user</td>
</tr>
<tr>
<td>6b616635-ae58-433a-a918-8c45e4f304dc</td>
<td>VirtualEvent.Read</td>
<td>Global Reader</td>
<td>Allows the app to read virtual events created by you</td>
<td>Read your virtual events</td>
</tr>
<tr>
<td>d38d189c-e29b-4344-8b3b-829bfa81380b</td>
<td>VirtualEvent.ReadWrite</td>
<td>Teams Administrator</td>
<td>Allows the app to read and write virtual events for you</td>
<td>Read and write your virtual events</td>
</tr>
<tr>
<td>11776c0c-6138-4db3-a668-ee621bea2555</td>
<td>WindowsUpdates.ReadWrite.All</td>
<td>Windows Update Deployment Administrator</td>
<td>Allows the app to read and write all Windows update deployment settings for the organization on behalf of the signed-in user.</td>
<td>Read and write all Windows update deployment settings</td>
</tr>
<tr>
<td>f1ccd5a7-6383-466a-8db8-1a656f7d06fa</td>
<td>WorkforceIntegration.Read.All</td>
<td>Global Reader</td>
<td>Allows the app to read workforce integrations, to synchronize data from Microsoft Teams Shifts, on behalf of the signed-in user.</td>
<td>Read workforce integrations</td>
</tr>
<tr>
<td>08c4b377-0d23-4a8b-be2a-23c1c1d88545</td>
<td>WorkforceIntegration.ReadWrite.All</td>
<td>Teams Administrator</td>
<td>Allows the app to manage workforce integrations, to synchronize data from Microsoft Teams Shifts, on behalf of the signed-in user.</td>
<td>Read and write workforce integrations</td>
</tr>
</tbody></table>