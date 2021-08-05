
# VMware Horizon (2106) Events

**Number of Events:** 858

| EventId | EventMessage |
|------------|-----------|
| ADMIN_ADD_DESKTOP_ENTITLEMENT | ${EntitlementDisplay} was entitled to Pool ${DesktopId} by ${UserDisplayName} |
| ADMIN_ADD_LICENSE | ${UserDisplayName} added license |
| ADMIN_ADD_LICENSE_FAILED | ${UserDisplayName} failed to add license |
| ADMIN_ADD_PM | ${UserDisplayName} added physical machine ${MachineName} to Pool  ${DesktopId} |
| ADMIN_ADD_PM_FAILED | ${UserDisplayName} failed to add physical machine ${MachineName} to Pool  ${DesktopId} |
| ADMIN_ADD_THINAPP_ENTITLEMENT | Application ${ThinAppDisplayName} was assigned to Desktop ${MachineName} by ${UserDisplayName} |
| ADMIN_ADD_THINAPP_ENTITLEMENT_FAILED | ${UserDisplayName} failed to add Application entitlement |
| ADMIN_ADD_THINAPP_POOL_ENTITLEMENT | Application ${ThinAppDisplayName} was assigned to Pool ${DesktopId} by ${UserDisplayName} |
| ADMIN_ADD_VM | ${UserDisplayName} has added machine ${MachineName} |
| ADMIN_ADMINSTRATOR_REMOVE_FAILED | ${UserDisplayName} failed to remove all permissions for Administrator ${AdminPermissionEntity} |
| ADMIN_ADMINSTRATOR_REMOVED | ${UserDisplayName} removed all permissions for Administrator ${AdminPermissionEntity} |
| ADMIN_BROKER_BROADCASTMSG | ${UserDisplayName} broadcasted message (${SessionMessage}) to all active sessions in Broker |
| ADMIN_BROKER_BROADCASTMSG_FAILED | ${UserDisplayName} failed to broadcast message (${SessionMessage}) to all active sessions in Broker |
| ADMIN_CCU_RESET | ${UserDisplayName} reset highest concurrent connection session counter, Highest CCU count: ${CCUCount} |
| ADMIN_CONFIGURE_TRANSFER_SERVER_LOCAL_REPO | ${UserDisplayName} configured a local Transfer Server Repository. Path ${PathName}. |
| ADMIN_CONFIGURE_TRANSFER_SERVER_LOCAL_REPO_FAILED | ${UserDisplayName} failed to configure a local Transfer Server Repository. Path ${PathName}. |
| ADMIN_CONFIGURE_TRANSFER_SERVER_NETWORK_REPO | ${UserDisplayName} configured a network Transfer Server Repository. Path: ${PathName}, domain: ${DomainName}, user name ${DomainUser} |
| ADMIN_CONFIGURE_TRANSFER_SERVER_NETWORK_REPO_FAILED | ${UserDisplayName} failed to configure a network Transfer Server Repository. Path: ${PathName}, domain: ${DomainName}, user name ${DomainUser} |
| ADMIN_CONNECTION_BROKER_UPDATE_FAILED | ${UserDisplayName} failed to update connection broker ${BrokerId} |
| ADMIN_CONNECTION_BROKER_UPDATED | ${UserDisplayName} updated connection broker ${BrokerId}: (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| ADMIN_CONNECTION_SERVER_BACKUP_FAILED | ${UserDisplayName} failed to initiate a backup of connection broker ${BrokerId} |
| ADMIN_CONNECTION_SERVER_BACKUP_INITIATED | ${UserDisplayName} initiated a backup of connection broker ${BrokerId} |
| ADMIN_CONNECTION_SERVER_DISABLE_FAILED | ${UserDisplayName} failed to disable connection broker ${BrokerId} |
| ADMIN_CONNECTION_SERVER_DISABLED | ${UserDisplayName} is disabling connection broker ${BrokerId} |
| ADMIN_CONNECTION_SERVER_ENABLE_FAILED | ${UserDisplayName} failed to enable connection broker ${BrokerId} |
| ADMIN_CONNECTION_SERVER_ENABLED | ${UserDisplayName} is enabling connection broker ${BrokerId} |
| ADMIN_CS_REGISTER_FAILED | ${UserDisplayName} failed to register Connection Server with ${AttrName}   ${AttrValue} |
| ADMIN_CS_REGISTERED | ${UserDisplayName} registered Connection Server with ${AttrName}   ${AttrValue} |
| ADMIN_CS_UNREGISTER_FAILED | ${UserDisplayName} failed to unregister Connection Server ${ConnectionServerAddress} |
| ADMIN_CS_UNREGISTERED | ${UserDisplayName} unregistered Connection Server ${ConnectionServerAddress} |
| ADMIN_DATABASE_CONFIGURATION_ADD_FAILED | ${UserDisplayName} failed to add database configuration |
| ADMIN_DATABASE_CONFIGURATION_ADDED | ${UserDisplayName} has added database configuration |
| ADMIN_DATABASE_CONFIGURATION_CHANGE_ATTEMPTED | ${UserDisplayName} has attempted to change event configuration |
| ADMIN_DATABASE_CONFIGURATION_DELETE_FAILED | ${UserDisplayName} failed to delete database configuration |
| ADMIN_DATABASE_CONFIGURATION_DELETED | ${UserDisplayName} has deleted database configuration |
| ADMIN_DATABASE_CONFIGURATION_UPDATE_FAILED | ${UserDisplayName} failed to update database configuration |
| ADMIN_DATABASE_CONFIGURATION_UPDATED | ${UserDisplayName} has updated database configuration |
| ADMIN_DATARECOVERY_PASSWD_CHANGE_FAILED | ${UserDisplayName} failed in changing data recovery password |
| ADMIN_DATARECOVERY_PASSWD_CHANGE_SUCCEEDED | ${UserDisplayName} succeeded in changing data recovery password |
| ADMIN_DEFAULT_DESKTOPPOOL_ASSIGN | ${UserDisplayName} assigned Pool ${DesktopId} for default desktop to ${UserName} |
| ADMIN_DEFAULT_DESKTOPPOOL_ASSIGN_FAILED | ${UserDisplayName} failed to assign Pool ${DesktopId} for default desktop to ${UserName} |
| ADMIN_DEFAULT_DESKTOPPOOL_UNASSIGN | ${UserDisplayName} removed pool assignment for default desktop to ${UserName} |
| ADMIN_DEFAULT_DESKTOPPOOL_UNASSIGN_FAILED | ${UserDisplayName} failed to remove Pool assignment for default desktop to ${UserName} |
| ADMIN_DELETE_PACKAGE | ${UserDisplayName} deleted transfer package ${PackageName}. |
| ADMIN_DELETE_PACKAGE_FAILED | ${UserDisplayName} failed to delete transfer package ${PackageName}. |
| ADMIN_DESKTOP_ADDED | ${UserDisplayName} added Pool ${DesktopId} |
| ADMIN_DESKTOP_ASSIGN | ${UserDisplayName} assigned Desktop ${MachineName} to ${UserName} |
| ADMIN_DESKTOP_ASSIGN_FAILED | ${UserDisplayName} failed to assign Desktop ${MachineName} to ${UserName} |
| ADMIN_DESKTOP_EDITED | ${UserDisplayName} edited Pool ${DesktopId} (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| ADMIN_DESKTOP_ENTITLEMENT_FAILED | ${UserDisplayName} failed to add or edit Pool entitlement ${DesktopId} |
| ADMIN_DESKTOP_MAINTENANCE_MODE_UPDATE_FAILED | ${UserDisplayName} failed to update desktop ${MachineName} to ${MaintenanceMode} maintenance mode |
| ADMIN_DESKTOP_MAINTENANCE_MODE_UPDATED | ${UserDisplayName} updated desktop ${MachineName} to ${MaintenanceMode} maintenance mode |
| ADMIN_DESKTOP_SESSION_DISCONNECT_FAILED | ${UserDisplayName} failed to disconnect ${UserName} from machine ${MachineName} |
| ADMIN_DESKTOP_SESSION_DISCONNECTED | ${UserDisplayName} has disconnected ${UserName} from machine ${MachineName} |
| ADMIN_DESKTOP_SESSION_LOGOFF | ${UserDisplayName} has logged off ${UserName} from machine ${MachineName} |
| ADMIN_DESKTOP_SESSION_LOGOFF_FAILED | ${UserDisplayName} failed to log off ${UserName} from machine ${MachineName} |
| ADMIN_DESKTOP_SESSION_RESET | ${UserDisplayName} has reset machine ${MachineName} |
| ADMIN_DESKTOP_SESSION_RESET_FAILED | ${UserDisplayName} failed to reset machine ${MachineName} |
| ADMIN_DESKTOP_SESSION_RESTART_FAILED | ${UserDisplayName} failed to restart machine ${MachineName} |
| ADMIN_DESKTOP_SESSION_RESTARTED | ${UserDisplayName} has restarted machine ${MachineName} |
| ADMIN_DESKTOP_UNASSIGN | ${UserDisplayName} removed assignment for Desktop ${MachineName} |
| ADMIN_DESKTOP_UNASSIGN_FAILED | ${UserDisplayName} failed to remove assignment for Desktop ${MachineName} |
| ADMIN_DIAG_OPERATION_SEND_FAILED | ${UserDisplayName} failed to send the diag operation to Diagnostic Agent, reason: ${DiagOperationFailedReason} |
| ADMIN_DIAG_OPERATION_SEND_SUCCEEDED | ${UserDisplayName} successfully sent the diag operation to Diagnostic agent |
| ADMIN_ENABLE_DESKTOP_FAILED | ${UserDisplayName} failed to set Pool ${DesktopId} to ${EnableStatus} |
| ADMIN_ENABLE_DESKTOP_SUCCEEDED | ${UserDisplayName} set Pool ${DesktopId} to ${EnableStatus} |
| ADMIN_ENABLED_DESKTOP_PROVISION_FAILED | ${UserDisplayName} failed to set provisioning for Pool ${PoolId} to ${EnableStatus} |
| ADMIN_ENABLED_DESKTOP_PROVISION_SUCCEEDED | ${UserDisplayName} set provisioning for Pool ${PoolId} to ${EnableStatus} |
| ADMIN_ENDPOINT_ASSIGNMENT_FAILED | User ${UserDisplayName} failed to assign endpoint ${EndpointDisplayName} |
| ADMIN_ENDPOINT_ASSIGNMENT_SUCCEEDED | User ${UserDisplayName} assigned endpoint ${EndpointDisplayName} to ${EndpointOwnerDisplayName} |
| ADMIN_ENDPOINT_CANCEL_FAILED | User ${UserDisplayName} failed to cancel ${EndpointCount} task(s) |
| ADMIN_ENDPOINT_CANCEL_SUCCEEDED | User ${UserDisplayName} canceled ${EndpointCount} task(s) |
| ADMIN_ENDPOINT_CHALLENGE_FAILED | User ${UserDisplayName} failed to obtain challenge response for endpoint ${EndpointDisplayName} |
| ADMIN_ENDPOINT_CHALLENGE_SUCCEEDED | User ${UserDisplayName} obtained challenge response for endpoint ${EndpointDisplayName} |
| ADMIN_ENDPOINT_ENABLE_REREGISTRATION_FAILED | User ${UserDisplayName} failed to enable reregistration for ${EndpointDisplayName} |
| ADMIN_ENDPOINT_ENABLE_REREGISTRATION_SUCCEEDED | User ${UserDisplayName} enabled reregistration for ${EndpointDisplayName} |
| ADMIN_ENDPOINT_REMOVE_FAILED | User ${UserDisplayName} failed to remove endpoint ${EndpointDisplayName} |
| ADMIN_ENDPOINT_REMOVE_SUCCEEDED | User ${UserDisplayName} removed endpoint ${EndpointDisplayName} |
| ADMIN_ENDPOINT_RENAME_FAILED | User ${UserDisplayName} failed to rename endpoint ${EndpointDisplayName} |
| ADMIN_ENDPOINT_RENAME_SUCCEEDED | User ${UserDisplayName} renamed endpoint ${EndpointPreviousDisplayName} to ${EndpointDisplayName} |
| ADMIN_ENDPOINT_REVERT_FAILED | User ${UserDisplayName} failed to start endpoint revert |
| ADMIN_ENDPOINT_REVERT_SUCCEEDED | User ${UserDisplayName} started revert of ${EndpointCount} endpoint(s) |
| ADMIN_ENDPOINT_SET_ACTIVE_DIRECTORY_CREDENTIALS_FAILED | User ${UserDisplayName} failed to set Active Directory credentials |
| ADMIN_ENDPOINT_SET_ACTIVE_DIRECTORY_CREDENTIALS_SUCCEEDED | User ${UserDisplayName} set Active Directory credentials |
| ADMIN_ENDPOINT_SET_CHECK_TLS_CERTIFICATE_FAILED | User ${UserDisplayName} failed to set check AMT TLS certificate to ${AmtSetting} |
| ADMIN_ENDPOINT_SET_CHECK_TLS_CERTIFICATE_SUCCEEDED | User ${UserDisplayName} set check AMT TLS certificate to ${AmtSetting} |
| ADMIN_ENDPOINT_SET_DESCRIPTION_FAILED | User ${UserDisplayName} failed to set description for endpoint ${EndpointDisplayName} |
| ADMIN_ENDPOINT_SET_DESCRIPTION_SUCCEEDED | User ${UserDisplayName} set description for endpoint ${EndpointDisplayName} |
| ADMIN_ENDPOINT_SET_DIGEST_CREDENTIALS_FAILED | User ${UserDisplayName} failed to set digest credentials |
| ADMIN_ENDPOINT_SET_DIGEST_CREDENTIALS_SUCCEEDED | User ${UserDisplayName} set digest credentials |
| ADMIN_ENDPOINT_SET_FOLDER_FAILED | User ${UserDisplayName} failed to set folder for endpoint ${EndpointDisplayName} |
| ADMIN_ENDPOINT_SET_FOLDER_SUCCEEDED | User ${UserDisplayName} set folder for endpoint ${EndpointDisplayName} to ${EndpointAdminFolderName} |
| ADMIN_ENDPOINT_SET_PREFERENCES_FAILED | User ${UserDisplayName} failed to set preferences for ${EndpointDisplayName} |
| ADMIN_ENDPOINT_SET_PREFERENCES_SUCCEEDED | User ${UserDisplayName} set preferences for ${EndpointDisplayName} |
| ADMIN_ENDPOINT_SET_REQUIRE_TLS_FAILED | User ${UserDisplayName} failed to set AMT TLS communication to ${AmtSetting} |
| ADMIN_ENDPOINT_SET_REQUIRE_TLS_SUCCEEDED | User ${UserDisplayName} set AMT TLS communication to ${AmtSetting} |
| ADMIN_ENDPOINT_TEST_AMT_MANAGEABILITY_FAILED | User ${UserDisplayName} failed to test AMT manageability for ${EndpointDisplayName} |
| ADMIN_ENDPOINT_TEST_AMT_MANAGEABILITY_SUCCEEDED | User ${UserDisplayName} tested AMT manageability for ${EndpointDisplayName} |
| ADMIN_ENDPOINT_UNASSIGNMENT_FAILED | User ${UserDisplayName} failed to unassign endpoint ${EndpointDisplayName} |
| ADMIN_ENDPOINT_UNASSIGNMENT_SUCCEEDED | User ${UserDisplayName} unassigned endpoint ${EndpointDisplayName} |
| ADMIN_ENDPOINT_UPGRADE_FAILED | User ${UserDisplayName} failed to start endpoint upgrade |
| ADMIN_ENDPOINT_UPGRADE_SUCCEEDED | User ${UserDisplayName} started upgrade of ${EndpointCount} endpoint(s) |
| ADMIN_EVENT_CONFIGURATION_UPDATE_FAILED | ${UserDisplayName} failed to update event configuration |
| ADMIN_EVENT_CONFIGURATION_UPDATED | ${UserDisplayName} has updated event configuration |
| ADMIN_FOLDER_ADD_FAILED | ${UserDisplayName} failed to add access group ${AdminFolderName} |
| ADMIN_FOLDER_ADDED | ${UserDisplayName} added access group ${AdminFolderName} |
| ADMIN_FOLDER_CHANGE_FAILED | ${UserDisplayName} failed to change object ${ObjectID}(type ${ObjectType}) to access group ${AdminFolderName} |
| ADMIN_FOLDER_CHANGED | ${UserDisplayName} changed object ${ObjectID}(type ${ObjectType}) to access group ${AdminFolderName} |
| ADMIN_FOLDER_DELETE_FAILED | ${UserDisplayName} failed to delete access group ${AdminFolderName} |
| ADMIN_FOLDER_DELETED | ${UserDisplayName} deleted access group ${AdminFolderName} |
| ADMIN_GLOBAL_CONFIGURATION_UPDATE_FAILED | ${UserDisplayName} failed to update global configuration |
| ADMIN_GLOBAL_CONFIGURATION_UPDATED | ${UserDisplayName} updated global configuration (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| ADMIN_GLOBAL_FOLDER_ADDED | ${UserDisplayName} added global access group ${AdminGlobalFolderName} |
| ADMIN_GLOBAL_FOLDER_DELETED | ${UserDisplayName} deleted global access group ${AdminGlobalFolderName} |
| ADMIN_GLOBAL_POLICY_UPDATE_FAILED | ${UserDisplayName} failed to update global policies |
| ADMIN_GLOBAL_POLICY_UPDATED | ${UserDisplayName} updated global policy (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| ADMIN_LIC_USAGE_RESET | ${UserDisplayName} reset session usage counters |
| ADMIN_LOCALMODE_INITIATE_REPLICATION | Initiate replication for Machine ${MachineName}. |
| ADMIN_LOCALMODE_LOCK_MACHINE | Lock Machine ${MachineName} on vCenter. |
| ADMIN_LOCALMODE_LOCK_MACHINE_FAILED | Lock Machine ${MachineName} failed on vCenter. |
| ADMIN_LOCALMODE_ROLLBACK_DESKTOP | Machine ${MachineName} has been rolled back. |
| ADMIN_LOCALMODE_UNLOCK_MACHINE | Unlock Machine ${MachineName} on vCenter. |
| ADMIN_LOCALMODE_UNLOCK_MACHINE_FAILED | Unlock Machine ${MachineName} failed on vCenter. |
| ADMIN_LOGIN_FAIL | User login attempt has failed to authenticate to View Administrator with username and password |
| ADMIN_LOGIN_FAIL_SMARTCARD | User login attempt has failed to authenticate to View Administrator with smart card |
| ADMIN_LS_CONFIGURE_FAILED | ${UserDisplayName} failed to configure Lookup Server ${LookupServerAddress} |
| ADMIN_LS_CONFIGURED | ${UserDisplayName} configured Lookup Server ${LookupServerAddress} |
| ADMIN_LS_CONFIGURED_WITH_THUMBPRINT | ${UserDisplayName} configured Lookup Server ${LookupServerAddress} with thumbprint |
| ADMIN_LS_UNCONFIGURE_FAILED | ${UserDisplayName} failed to remove Lookup Server ${LookupServerAddress} |
| ADMIN_LS_UNCONFIGURED | ${UserDisplayName} removed Lookup Server ${LookupServerAddress} |
| ADMIN_NU_RESET | ${UserDisplayName} reset named user session counter, Current NU Count: ${NUCount} |
| ADMIN_PERFMON_CONFIGURATION_UPDATE_FAILED | ${UserDisplayName} failed to update performance monitoring configuration |
| ADMIN_PERFMON_CONFIGURATION_UPDATED | ${UserDisplayName} has updated performance monitoring configuration |
| ADMIN_PERMISSION_ADD_FAILED | ${UserDisplayName} failed to add Permission to ${AdminPermissionEntity} with Role ${AdminRoleName} on Access Group ${AdminFolderName} |
| ADMIN_PERMISSION_ADDED | ${UserDisplayName} added Permission to ${AdminPermissionEntity} with Role ${AdminRoleName} on Access Group ${AdminFolderName} |
| ADMIN_PERMISSION_REMOVE_FAILED | ${UserDisplayName} failed to remove Permission to ${AdminPermissionEntity} with Role ${AdminRoleName} on Access Group ${AdminFolderName} |
| ADMIN_PERMISSION_REMOVED | ${UserDisplayName} removed Permission to ${AdminPermissionEntity} with Role ${AdminRoleName} on Access Group ${AdminFolderName} |
| ADMIN_POOL_ADD_FAILED | ${UserDisplayName} failed to add Pool ${DesktopId} |
| ADMIN_POOL_BROADCASTMSG | ${UserDisplayName} broadcasted message (${SessionMessage}) to Pool ${PoolId} |
| ADMIN_POOL_BROADCASTMSG_FAILED | ${UserDisplayName} failed to broadcast message (${SessionMessage}) to Pool ${PoolId} |
| ADMIN_POOL_POLICY_UPDATE_FAILED | ${UserDisplayName} failed to update Pool ${DesktopId} policies |
| ADMIN_POOL_POLICY_UPDATED | ${UserDisplayName} updated Pool ${DesktopId} policy (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| ADMIN_PUBLISH_PACKAGE | ${UserDisplayName} published transfer package ${PackageName}. |
| ADMIN_PUBLISH_PACKAGE_FAILED | ${UserDisplayName} failed to publish transfer package ${PackageName}. |
| ADMIN_RADIUS_AUTHENTICAOR_ADD_FAILED | Failed to add RADIUS Authenticator ${RADIUSAuthenticatorName} |
| ADMIN_RADIUS_AUTHENTICAOR_ADDED | RADIUS Authenticator ${RADIUSAuthenticatorName} added |
| ADMIN_RADIUS_AUTHENTICAOR_REMOVE_FAILED | Failed to remove RADIUS Authenticator ${RADIUSAuthenticatorName} |
| ADMIN_RADIUS_AUTHENTICAOR_REMOVED | RADIUS Authenticator ${RADIUSAuthenticatorName} removed |
| ADMIN_RADIUS_AUTHENTICAOR_UPDATE_FAILED | Failed to update RADIUS Authenticator ${RADIUSAuthenticatorName} |
| ADMIN_RADIUS_AUTHENTICAOR_UPDATED | RADIUS Authenticator ${RADIUSAuthenticatorName} updated |
| ADMIN_REMOVE_DESKTOP_ENTITLEMENT | ${EntitlementDisplay} was unentitled from Pool ${DesktopId} by ${UserDisplayName} |
| ADMIN_REMOVE_DESKTOP_FAILED | ${UserDisplayName} failed to removed Pool ${DesktopId} |
| ADMIN_REMOVE_DESKTOP_SUCCEEDED | ${UserDisplayName} removed Pool ${DesktopId} |
| ADMIN_REMOVE_THINAPP_ENTITLEMENT | Application ${ThinAppDisplayName} was unassigned from Desktop ${MachineName} by ${UserDisplayName} |
| ADMIN_REMOVE_THINAPP_ENTITLEMENT_FAILED | ${UserDisplayName} failed to remove Application entitlement |
| ADMIN_REMOVE_THINAPP_POOL_ENTITLEMENT | Application ${ThinAppDisplayName} was unassigned from Pool ${DesktopId} by ${UserDisplayName} |
| ADMIN_RESET_THINAPP_STATE | Application ${ThinAppDisplayName} state was reset for Desktop ${DesktopDisplayName} by ${UserDisplayName} |
| ADMIN_RESET_THINAPP_STATE_FAILED | ${UserDisplayName} failed to reset Application ${ThinAppDisplayName} state for  Desktop ${DesktopDisplayName} |
| ADMIN_RESET_VM | ${UserDisplayName} has reset machine ${MachineName} |
| ADMIN_RESET_VM_FAIL | ${UserDisplayName} has failed to reset machine ${MachineName} |
| ADMIN_RESTART_VM | ${UserDisplayName} has restarted machine ${MachineName} |
| ADMIN_RESTART_VM_FAIL | ${UserDisplayName} failed to restart machine ${MachineName} |
| ADMIN_ROLE_ADD_FAILED | ${UserDisplayName} failed to add Role ${AdminRoleName} with privileges ${AdminPrivilegeName} |
| ADMIN_ROLE_ADDED | ${UserDisplayName} added Role ${AdminRoleName} with privileges ${AdminPrivilegeName} |
| ADMIN_ROLE_PRIV_UPDATE_FAILED | ${UserDisplayName} failed to update Role ${AdminRoleName} to privileges ${AdminPrivilegeName} |
| ADMIN_ROLE_PRIV_UPDATED | ${UserDisplayName} updated Role ${AdminRoleName} to privileges ${AdminPrivilegeName} |
| ADMIN_ROLE_REMOVE_FAILED | ${UserDisplayName} failed to remove Role ${AdminRoleName} |
| ADMIN_ROLE_REMOVED | ${UserDisplayName} removed Role ${AdminRoleName} |
| ADMIN_ROLE_RENAME_FAILED | ${UserDisplayName} failed to rename Role ${AdminRoleName} to ${AdminRoleNewName} |
| ADMIN_ROLE_RENAMED | ${UserDisplayName} renamed Role ${AdminRoleName} to ${AdminRoleNewName} |
| ADMIN_SAM_AUTHENTICATOR_ADD_FAILED | Failed to add SAML Authenticator ${SAMLAuthenticatorLabel} |
| ADMIN_SAM_AUTHENTICATOR_ADDED | SAML Authenticator ${SAMLAuthenticatorLabel} added |
| ADMIN_SAM_AUTHENTICATOR_REMOVE_FAILED | Failed to remove SAML Authenticator ${SAMLAuthenticatorLabel} |
| ADMIN_SAM_AUTHENTICATOR_REMOVED | SAML Authenticator ${SAMLAuthenticatorLabel} removed |
| ADMIN_SAM_AUTHENTICATOR_UPDATE_FAILED | Failed to update SAML Authenticator ${SAMLAuthenticatorLabel} |
| ADMIN_SAM_AUTHENTICATOR_UPDATED | SAML Authenticator ${SAMLAuthenticatorLabel} updated |
| ADMIN_SECURITY_SERVER_ADD_FAILED | ${UserDisplayName} failed to add security server ${SecurityServerId} |
| ADMIN_SECURITY_SERVER_ADDED | ${UserDisplayName} added security server ${SecurityServerId} |
| ADMIN_SECURITY_SERVER_EDIT_FAILED | ${UserDisplayName} failed to edit security server ${SecurityServerId} |
| ADMIN_SECURITY_SERVER_EDITED | ${UserDisplayName} edited security server ${SecurityServerId} (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| ADMIN_SECURITY_SERVER_IPSECRULES_DELETE_FAILED | ${UserDisplayName} failed to delete IPSec Rules for security server ${SecurityServerId} |
| ADMIN_SECURITY_SERVER_REMOVE_FAILED | ${UserDisplayName} failed to remove security server ${SecurityServerId} |
| ADMIN_SECURITY_SERVER_REMOVED | ${UserDisplayName} removed security server ${SecurityServerId} |
| ADMIN_SESSION_SENDMSG | ${UserDisplayName} sent message (${SessionMessage}) to session (User ${UserName}, Desktop ${MachineName}) |
| ADMIN_SESSION_SENDMSG_FAILED | ${UserDisplayName} failed to send message (${SessionMessage}) to session ${ObjectId} |
| ADMIN_SVI_ADD_DEPLOYMENT_GROUP_FAILED | Failed to add deployment group for ${SVIParentVM} : ${SVISnapshot} |
| ADMIN_SVI_ADD_DEPLOYMENT_GROUP_SUCCEEDED | Added deployment group ${SVIDeploymentGroupID} for ${SVIParentVM} : ${SVISnapshot} |
| ADMIN_SVI_ADD_UDD_FAILED | Failed to add user data disk ${UserDiskName} |
| ADMIN_SVI_ADD_UDD_SUCCEEDED | Added user data disk ${UserDiskName} |
| ADMIN_SVI_ADMIN_ADDED | ${UserDisplayName} added SVI QuickPrep domain ${SVIAdminFqdn}(${SVIAdminName}) |
| ADMIN_SVI_ADMIN_REMOVED | ${UserDisplayName} removed SVI QuickPrep domain ${SVIAdminFqdn}(${SVIAdminName}), (id ${SVIAdminID}) |
| ADMIN_SVI_ADMIN_UPDATED | ${UserDisplayName} updated SVI QuickPrep domain ${SVIAdminFqdn}(${SVIAdminName}) |
| ADMIN_SVI_ATTACH_UDD_FAILED | Failed to request attach user data disk ${UserDiskName} to VM ${SVIVMID} |
| ADMIN_SVI_ATTACH_UDD_SUCCEEDED | Requested attach user data disk ${UserDiskName} to VM ${SVIVMID} |
| ADMIN_SVI_DELETE_UDD_FAILED | Failed to delete user data disk ${UserDiskName} |
| ADMIN_SVI_DELETE_UDD_SUCCEEDED | Deleted user data disk ${UserDiskName} |
| ADMIN_SVI_DETACH_UDD_FAILED | Failed to request detach user data disk ${UserDiskName} from VM ${SVIVMID} |
| ADMIN_SVI_DETACH_UDD_SUCCEEDED | Requested detach user data disk ${UserDiskName} from VM ${SVIVMID} |
| ADMIN_SVI_REBALANCE_VM_FAILED | Failed to rebalance VM ${SVIVMID} |
| ADMIN_SVI_REBALANCE_VM_SUCCEEDED | Rebalanced VM ${SVIVMID} |
| ADMIN_SVI_REFRESH_VM_FAILED | Failed to refresh VM ${SVIVMID} |
| ADMIN_SVI_REFRESH_VM_SUCCEEDED | Refreshed VM ${SVIVMID} |
| ADMIN_SVI_REPLACE_UDD_FAILED | Failed to replace to user data disk ${UserDiskName} for VM ${SVIVMID} |
| ADMIN_SVI_REPLACE_UDD_SUCCEEDED | Replaced user data disk ${UserDiskName} for VM ${SVIVMID} |
| ADMIN_SVI_RESYNC_VM_FAILED | Failed to resync VM ${SVIVMID} to deployment group ${SVIDeploymentGroupID} |
| ADMIN_SVI_RESYNC_VM_SUCCEEDED | Resyncd VM ${SVIVMID} to deployment group ${SVIDeploymentGroupID} |
| ADMIN_SVI_TASK_CANCEL_FAILED | ${UserDisplayName} failed to cancel ${SVIOperation} for Machine ${MachineName} |
| ADMIN_SVI_TASK_CANCELED | ${UserDisplayName} canceled ${SVIOperation} for Machine ${MachineName} |
| ADMIN_SVI_TASK_HELD | ${UserDisplayName} paused ${SVIOperation} for Machine ${MachineName} |
| ADMIN_SVI_TASK_HOLD_FAILED | ${UserDisplayName} failed to pause ${SVIOperation} for Machine ${MachineName} |
| ADMIN_SVI_TASK_RESUME_FAILED | ${UserDisplayName} failed to resume ${SVIOperation} for Machine ${MachineName} |
| ADMIN_SVI_TASK_RESUMED | ${UserDisplayName} resumed ${SVIOperation} for Machine ${MachineName} |
| ADMIN_SVI_UPDATE_POOL_DEPLOYMENT_GROUP_FAILED | ${UserDisplayName} failed to update pool ${PoolId} to deployment group ${SVIDeploymentGroupID} for ${SVIParentVM} : ${SVISnapshot} |
| ADMIN_SVI_UPDATE_POOL_DEPLOYMENT_GROUP_SUCCEEDED | ${UserDisplayName} updated pool ${PoolId} to deployment group ${SVIDeploymentGroupID} for ${SVIParentVM} : ${SVISnapshot} |
| ADMIN_SVI_UPDATE_UDD_FAILED | Failed to update user data disk ${UserDiskName} |
| ADMIN_SVI_UPDATE_UDD_SUCCEEDED | Set user data disk ${UserDiskName} pool to ${DesktopId} and user to ${UserName} |
| ADMIN_THINAPP_ADD_FAILED | ${UserDisplayName} failed to add Application ${ThinAppDisplayName} |
| ADMIN_THINAPP_ADDED | ${UserDisplayName} added Application ${ThinAppDisplayName} |
| ADMIN_THINAPP_DESKTOP_AVAILABLE | Application ${ThinAppDisplayName} is now available on Desktop ${DesktopDisplayName} |
| ADMIN_THINAPP_DESKTOP_REMOVED | Application ${ThinAppDisplayName} has been removed from Desktop ${DesktopDisplayName} |
| ADMIN_THINAPP_EDITED | ${UserDisplayName} edited Application ${ThinAppDisplayName} |
| ADMIN_THINAPP_FAILED_DESKTOP_DELIVERY | Failed to deliver Application ${ThinAppDisplayName} to Desktop ${DesktopDisplayName}, Error ${ErrorContext} ${ErrorDescription}   |
| ADMIN_THINAPP_FAILED_DESKTOP_REMOVAL | Failed to remove Application ${ThinAppDisplayName} from Desktop ${DesktopDisplayName}, Error ${ErrorContext} ${ErrorDescription} |
| ADMIN_THINAPP_GROUP_ADD_FAILED | ${UserDisplayName} failed to add Application Template ${ThinAppGroupName} |
| ADMIN_THINAPP_GROUP_ADDED | ${UserDisplayName} added Application Template ${ThinAppGroupName} with Applications ${ThinAppGroupApplications} |
| ADMIN_THINAPP_GROUP_EDIT_FAILED | ${UserDisplayName} failed to edit Application Template ${ThinAppGroupName} |
| ADMIN_THINAPP_GROUP_EDITED | ${UserDisplayName} edited Application Template ${ThinAppGroupName} with Applications ${ThinAppGroupApplications} |
| ADMIN_THINAPP_GROUP_REMOVE_FAILED | ${UserDisplayName} failed to remove Application Template ${ThinAppGroupName} |
| ADMIN_THINAPP_GROUP_REMOVED | ${UserDisplayName} removed Application Template ${ThinAppGroupName} |
| ADMIN_THINAPP_REMOVE_FAILED | ${UserDisplayName} failed to remove Application ${ThinAppDisplayName} |
| ADMIN_THINAPP_REMOVED | ${UserDisplayName} removed Application ${ThinAppDisplayName} |
| ADMIN_THINAPP_REPO_ADD_FAILED | ${UserDisplayName} failed to add Repository ${ThinAppRepositoryName}, path ${ThinAppRepositoryPath} |
| ADMIN_THINAPP_REPO_ADDED | ${UserDisplayName} added Repository ${ThinAppRepositoryName}, path ${ThinAppRepositoryPath} |
| ADMIN_THINAPP_REPO_EDIT_FAILED | ${UserDisplayName} failed to edit Repository ${ThinAppRepositoryName}, path ${ThinAppRepositoryPath} |
| ADMIN_THINAPP_REPO_EDITED | ${UserDisplayName} edited Repository ${ThinAppRepositoryName}, path ${ThinAppRepositoryPath} |
| ADMIN_THINAPP_REPO_REMOVED | ${UserDisplayName} removed Repository ${ThinAppRepositoryName} |
| ADMIN_TRANSFER_SERVER_ADD_FAILED | ${UserDisplayName} failed to add transfer server ${TransferServerDisplay} |
| ADMIN_TRANSFER_SERVER_ADDED | ${UserDisplayName} added transfer server ${TransferServerDisplay} |
| ADMIN_TRANSFER_SERVER_EDITED | ${UserDisplayName} edited transfer server ${TransferServerDisplay} (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| ADMIN_TRANSFER_SERVER_ENTER_MAINTENANCE | Transfer server ${TransferServerDisplay} enters maintenance mode |
| ADMIN_TRANSFER_SERVER_ENTER_MAINTENANCE_FAILED | Transfer server ${TransferServerId} failed to enter maintenance mode |
| ADMIN_TRANSFER_SERVER_EXIT_MAINTENANCE | Transfer server ${TransferServerDisplay} exits maintenance mode |
| ADMIN_TRANSFER_SERVER_EXIT_MAINTENANCE_FAILED | Transfer server ${TransferServerId} failed to exit maintenance mode |
| ADMIN_TRANSFER_SERVER_REMOVE_FAILED | ${UserDisplayName} failed to remove transfer server ${TransferServerId} |
| ADMIN_TRANSFER_SERVER_REMOVED | ${UserDisplayName} queued removal of transfer server ${TransferServerDisplay} |
| ADMIN_UNREGISTER_PM | ${UserDisplayName} unregistered physical machine ${MachineName} |
| ADMIN_UNREGISTER_PM_FAILED | ${UserDisplayName} fails to unregister physical machine ${MachineName} |
| ADMIN_USER_INFO_UPDATE_FAILED | ${UserDisplayName} failed to update user info with AD server for ${UserName} |
| ADMIN_USER_INFO_UPDATED | ${UserDisplayName} updated user info with AD server for ${UserName} |
| ADMIN_USER_POLICY_DELETE_FAILED | ${UserDisplayName} failed to delete Pool ${DesktopId} override policies for user ${UserName} |
| ADMIN_USER_POLICY_DELETED | ${UserDisplayName} deleted Pool ${DesktopId} override policy for user ${UserName} (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| ADMIN_USER_POLICY_UPDATE_FAILED | ${UserDisplayName} failed to update Pool ${DesktopId} policies for user ${UserName} |
| ADMIN_USER_POLICY_UPDATED | ${UserDisplayName} updated Pool ${DesktopId} policy for user ${UserName} (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| ADMIN_USERHINT_MISMATCH_SMARTCARD | UserNameHint mismatch with smart card |
| ADMIN_USERLOGGEDIN | User ${UserDisplayName} has logged in to View Administrator with username and password |
| ADMIN_USERLOGGEDIN_SMARTCARD | User ${UserDisplayName} has logged in to View Administrator with smart card |
| ADMIN_USERLOGGEDOUT | User ${UserDisplayName} has logged out from View Administrator |
| ADMIN_USERLOGIN_FAIL | User ${UserDisplayName} has failed to authenticate to View Administrator |
| ADMIN_VC_ADD_FAILED | ${UserDisplayName} failed to add VC server ${VCAddress} |
| ADMIN_VC_ADDED | ${UserDisplayName} added VC server ${VCAddress} with deployment type ${VCDeploymentType} |
| ADMIN_VC_EDITED | ${UserDisplayName} edited VC server ${VCAddress} (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| ADMIN_VC_LICINV_ALARM_DISABLED | Alarm on VC server ${VCAddress} for License Inventory monitoring was disabled as all Hosts have desktop licenses  |
| ADMIN_VC_PROVISIONING_DISABLED | ${UserDisplayName} disabled provisioning on vCenter Server ${VCAddress} |
| ADMIN_VC_PROVISIONING_DISABLED_FAILED | ${UserDisplayName} failed to disable provisioning on vCenter Server ${VCAddress} |
| ADMIN_VC_PROVISIONING_ENABLED | ${UserDisplayName} enabled provisioning on vCenter Server ${VCAddress} |
| ADMIN_VC_PROVISIONING_ENABLED_FAILED | ${UserDisplayName} failed to enable provisioning on vCenter Server ${VCAddress} |
| ADMIN_VC_REMOVE_FAILED | ${UserDisplayName} failed to remove VC server ${VCAddress} |
| ADMIN_VC_REMOVED | ${UserDisplayName} removed VC server ${VCAddress} with deployment type ${VCDeploymentType} |
| AGENT_APPLICATION_LAUNCH_FAILED | Machine named ${MachineName} failed to launch application ${ApplicationExecutable} for user ${UserDisplayName} |
| AGENT_CONNECTED | User ${UserDisplayName} has logged in to a new session on machine ${MachineName} |
| AGENT_DISCONNECTED | User ${UserDisplayName} has disconnected from machine ${MachineName} |
| AGENT_ENDED | User ${UserDisplayName} has logged off machine ${MachineName} |
| AGENT_LAUNCH_FAILED | Failed to launch Machine ${MachineName} |
| AGENT_PENDING | The agent running on machine ${MachineName} has accepted an allocated session for user ${UserDisplayName} |
| AGENT_PENDING_EXPIRED | The pending session on machine ${MachineName} for user ${UserDisplayName} has expired |
| AGENT_RECONFIGURED | Machine ${MachineName} has been successfully reconfigured |
| AGENT_RECONNECTED | User ${UserDisplayName} has reconnected to machine ${MachineName} |
| AGENT_RESUME | The agent on machine ${MachineName} sent a resume message |
| AGENT_SHUTDOWN | The agent running on machine ${MachineName} has shut down, this machine will be unavailable |
| AGENT_STARTUP | The agent running on machine ${MachineName} has contacted the connection server and sent a startup message |
| AGENT_SUSPEND | The agent on machine ${MachineName} sent a suspend message |
| AGENT_UNMANAGED_REGISTRATION | A machine named ${MachineName} was registered for use with View. |
| AUXILIARY_ACCOUNT_ADD_SUCCESS | User ${UserDisplayName} successfully added auxiliary account with username ${AuxiliaryAccount} to the No-Trust domain ${Domain}. |
| AUXILIARY_ACCOUNT_DELETE_SUCCESS | User ${UserDisplayName} successfully deleted auxiliary account with id ${AuxiliaryAccount} from the No-Trust domain ${Domain}. |
| AUXILIARY_ACCOUNT_UPDATE_SUCCESS | User ${UserDisplayName} successfully updated auxiliary account with id ${AuxiliaryAccount} for the No-Trust domain ${Domain}. |
| BROKER_AGENT_OFFLINE | The agent running on machine ${MachineName} has not responded to queries, marking it as offline |
| BROKER_AGENT_ONLINE | The agent running on machine ${MachineName} is responding again, but did not send a startup message |
| BROKER_APPLICATION_LAUNCH_FAILURE | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: The broker encountered an error while processing the request, please contact support for assistance |
| BROKER_APPLICATION_MISSING | At least ${ApplicationMissingCount} applications, including ${ApplicationExecutable}, are not installed on ${MachineName} in Pool ${PoolId} |
| BROKER_APPLICATION_NOT_ENTITLED | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: User is not entitled to this Pool |
| BROKER_APPLICATION_PROTOCOL_NOT_SUPPORTED | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: Requested protocol ${ProtocolId} is not supported |
| BROKER_APPLICATION_REQUEST | User ${UserDisplayName} requested Application ${ApplicationId} |
| BROKER_APPLICATION_SESSION_REQUEST | User ${UserDisplayName} requested an application session from Pool ${PoolId}, pre-launch ${PreLaunchSession} |
| BROKER_BACKUP_FAILED | Backup of server ${BrokerName} failed with Error: ${BrokerBackupStatus} |
| BROKER_CONFIGURATION_CLIENT_CREDENTIAL_CACHING_DISABLED | Client credential caching is disabled |
| BROKER_CONFIGURATION_CLIENT_CREDENTIAL_CACHING_NO_TIMEOUT | Client credential caching is enabled, no timeout |
| BROKER_CONFIGURATION_CLIENT_CREDENTIAL_CACHING_TIMEOUT | Client credential caching is enabled, timeout ${AttrValue} minutes |
| BROKER_DAILY_MAX_APP_USERS | Over the past 24 hours, the maximum number of users with concurrent application sessions was ${UserCount} |
| BROKER_DAILY_MAX_CCU_USERS | Over the past 24 hours, the maximum number of concurrent connection sessions was ${CCUCount} |
| BROKER_DAILY_MAX_DESKTOP_SESSIONS | Over the past 24 hours, the maximum number of concurrent desktop sessions was ${UserCount} |
| BROKER_DAILY_MAX_NU_USERS | Over the past 24 hours, the maximum number of named user sessions was ${NUCount} |
| BROKER_DAILY_MAX_USERS | Over the past 24 hours, the maximum number of users with concurrent desktop sessions was ${UserCount} |
| BROKER_DESKTOP_LAUNCH_FAILURE | Unable to launch from Pool ${DesktopId} for user ${UserDisplayName}: The broker encountered an error while processing the request, please contact support for assistance |
| BROKER_DESKTOP_NOT_ENTITLED | Unable to launch from Pool ${DesktopId} for user ${UserDisplayName}: User is not entitled to this Pool |
| BROKER_DESKTOP_PROTOCOL_NOT_SUPPORTED | Unable to launch from Pool ${DesktopId} for user ${UserDisplayName}: Requested protocol ${ProtocolId} is not supported |
| BROKER_DESKTOP_REQUEST | User ${UserDisplayName} requested Pool ${DesktopId} |
| BROKER_EVENT_HANDLING_STARTED | Broker ${BrokerName} has started handling events |
| BROKER_EVENT_HANDLING_STOPPED | Broker ${BrokerName} has stopped handling events |
| BROKER_EVENT_SYSLOG_CONNECT_ERROR | Failed to connect to destination specified for syslog events (${SyslogPath}) with error ${SyslogErrorCode}: ${SyslogErrorDesc} |
| BROKER_LMV_POD_ENDPOINT_STATE_CHANGED | Pod Endpoint ${PodEndpointName} state has changed to ${PodEndpointNewState} |
| BROKER_LMV_POD_TIME_OUT_OF_SYNC | System time on pod ${PodName} differs from local system time by ${PodTimeDifference} seconds |
| BROKER_LMV_REMOTE_POD_APPLICATION_LAUNCH | Remote pod ${PodName} has launched an application for user ${UserName} from global application entitlement ${GlobalEntitlementName} |
| BROKER_LMV_REMOTE_POD_APPLICATION_RECONNECT | Remote pod ${PodName} has reconnected to existing application for user ${UserName} |
| BROKER_LMV_REMOTE_POD_DESKTOP_LAUNCH | Remote pod ${PodName} has launched a desktop for user ${UserName} from global entitlement ${GlobalEntitlementName} |
| BROKER_LMV_USER_GES_DISABLED | User ${UserDisplayName} has authenticated, but is only entitled to disabled global entitlements. |
| BROKER_LOCALMODE_CID_POPULATION_FAILURE | Unable to populate disk content ID during ${LocalModeOperation} for Desktop ${DesktopId}, Machine ${MachineName}, Disk paths ${DiskPath}. |
| BROKER_LOCALMODE_CID_VALIDATION_FAILURE | Disk content ID validation failed during ${LocalModeOperation} for Desktop ${DesktopId}, Machine ${MachineName}, Disk paths ${DiskPath}. |
| BROKER_LOCALMODE_OLD_ANCHOR_DELETE_FAILURE | Old anchor snapshot deletion task failed for Machine ${MachineName}.  Error message: ${LocalModeMessage} |
| BROKER_LOCALMODE_OPERATION_AUDIT_FAILURE | Local Mode Operation ${LocalModeOperation} failed for Desktop ${MachineName}, ID: ${DesktopId}.  Error message: ${LocalModeMessage} |
| BROKER_LOCALMODE_OPERATION_FAILURE | Local Mode Operation ${LocalModeOperation} failed for Desktop ${MachineName}, ID: ${DesktopId}. Error message: ${LocalModeMessage} |
| BROKER_LOCALMODE_OPERATION_SUCCESS | Local Mode Operation ${LocalModeOperation} has completed for Desktop ${MachineName}, ID: ${DesktopId}. |
| BROKER_MACHINE_ALLOCATED | User ${UserDisplayName} requested Pool ${PoolId}, allocated machine ${MachineName} |
| BROKER_MACHINE_ASSIGNED_BUSY | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: Assigned machine ${MachineName} is busy. |
| BROKER_MACHINE_ASSIGNED_UNAVAILABLE | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: Assigned machine ${MachineName} is unavailable |
| BROKER_MACHINE_CANNOT_CONNECT | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: Failed to connect to Machine ${MachineName} using ${ProtocolId} |
| BROKER_MACHINE_CHECKEDOUT | Unable to launch from Pool ${DesktopId} for user ${UserDisplayName}: VM ${MachineName} is currently checked out on a client device |
| BROKER_MACHINE_CONFIGURED_PAGE_SHARING_SETTINGS | Successfully configured page sharing settings for Machine VM ${MachineName} in Pool ${PoolId} |
| BROKER_MACHINE_CONFIGURED_VIDEO_SETTINGS | Successfully configured video settings for Machine VM ${MachineName} in Pool ${DesktopId} |
| BROKER_MACHINE_NOT_READY | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: Machine ${MachineName} is not ready to accept connections |
| BROKER_MACHINE_OPERATION_DELETED | machine ${MachineName} has been deleted |
| BROKER_MACHINE_POWERON_FAIL_MISSING_HARDWARE_RENDERER | Failed to power on VM ${MachineName} in Pool ${PoolId}: A hardware 3D renderer is not available on host ${EsxHostName}. |
| BROKER_MACHINE_PROTOCOL_NOT_SUPPORTED | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: Machine ${MachineName} does not support protocol ${ProtocolId} |
| BROKER_MACHINE_PROTOCOL_UNAVAILABLE | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: Machine ${MachineName} did not report protocol ${ProtocolId} as ready |
| BROKER_MACHINE_REJECTED_SESSION | Unable to launch from Pool ${DesktopId} for user ${UserDisplayName}: Machine ${MachineName} rejected the start session request |
| BROKER_MACHINE_SCREEN_DMA_CONFIG_FAILED | Failed to configure ScreenDMA config option for VM ${MachineName} in Pool ${DesktopId} |
| BROKER_MACHINE_SCREEN_DMA_CONFIGURED | Successfully configured ScreenDMA config option for VM ${MachineName} in Pool ${DesktopId} |
| BROKER_MACHINE_SESPARSE_RECLAMATION_FAILED | Failed to perform space reclamation on machine ${MachineName} in Pool ${PoolId} |
| BROKER_MACHINE_SESPARSE_RECLAMATION_SKIPPED_SVI_OPERATION | Space reclamation skipped for machine ${MachineName} in Pool ${PoolId} because it is scheduled for a View Composer task |
| BROKER_MACHINE_SESPARSE_RECLAMATION_SUCCESS | Successfully reclaimed ${MachineReclaimedSpaceAmountUnit} of space from machine ${MachineName} in Pool ${PoolId} on datastore ${MachineReclaimedSpaceDatastore} |
| BROKER_MACHINE_SESSION_TIMEDOUT | Session for user ${UserDisplayName} timed out |
| BROKER_MULTIPLE_DESKTOPS_FOR_KIOSK_USER | User ${UserDisplayName} is entitled to multiple desktop pools |
| BROKER_NETWORK_LABEL_ALL_CAPACITY_REACHED | All network label capacity has been reached on NIC ${NicName} for VM ${MachineName} in Pool ${PoolId} |
| BROKER_NETWORK_LABEL_CURRENT_CAPACITY_REACHED | Network label ${NetworkLabelName} on ${NicName} with capacity ${NetworkLabelCapacity} has been exhausted in Pool ${PoolId} |
| BROKER_POOL_CANNOT_ASSIGN | Unable to launch from Pool ${DesktopId} for user ${UserDisplayName}: There are no machines available to assign the user to |
| BROKER_POOL_COMANAGER_REQUIRED | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: No co-management availability for protocol ${ProtocolId} |
| BROKER_POOL_EMPTY | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: The Pool is empty |
| BROKER_POOL_NO_MACHINE_ASSIGNED | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: No machine assigned to this user |
| BROKER_POOL_NO_RESPONSES | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: No machines in the Pool are responsive |
| BROKER_POOL_NO_UNAUTHENTICATED_ACCESS_SUPPORT | Unable to launch application from Pool ${PoolId} for user ${UserDisplayName}: There were no machines available for unauthenticated access. |
| BROKER_POOL_OVERLOADED | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: All responding machines are currently in use |
| BROKER_POOL_POLICY_VIOLATION | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: This Pool does not allow online sessions |
| BROKER_POOL_PROTOCOL_NOT_SUPPORTED | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: There were no machines available that support protocol ${ProtocolId} |
| BROKER_POOL_PROTOCOL_UNAVAILABLE | Unable to launch from Pool ${PoolId} for user ${UserDisplayName}: There were no machines available that reported protocol ${ProtocolId} as ready |
| BROKER_POOL_TUNNEL_NOT_SUPPORTED | Unable to launch from Pool ${DesktopId} for user ${UserDisplayName}: Tunnelling is not supported for protocol ${ProtocolId} |
| BROKER_PROVISIONING_DISABLED | Provisioning disabled for Pool ${PoolId} |
| BROKER_PROVISIONING_ERROR_CONFIG_CLEARED | The previously reported configuration problem is no longer present on Pool ${PoolId} |
| BROKER_PROVISIONING_ERROR_CONFIG_SET | Provisioning error occurred on Pool ${PoolId} because of a configuration problem |
| BROKER_PROVISIONING_ERROR_DISK_CLEARED | The previously reported disk problem is no longer present on Pool ${PoolId} |
| BROKER_PROVISIONING_ERROR_DISK_SET | Provisioning error occurred on Pool ${PoolId} because of a disk problem |
| BROKER_PROVISIONING_ERROR_LICENCE_CLEARED | The previously reported licencing problem is no longer present on Pool ${PoolId} |
| BROKER_PROVISIONING_ERROR_LICENCE_SET | Provisioning error occurred on Pool ${PoolId} because of a licencing problem |
| BROKER_PROVISIONING_ERROR_NETWORKING_CLEARED | The previously reported networking problems with a View Agent are no longer present on Pool ${PoolId} |
| BROKER_PROVISIONING_ERROR_NETWORKING_SET | Provisioning error occurred on Pool ${PoolId} because of a networking problem with a View Agent |
| BROKER_PROVISIONING_ERROR_RESOURCE_CLEARED | The previously reported resource problem is no longer present on Pool ${PoolId} |
| BROKER_PROVISIONING_ERROR_RESOURCE_SET | Provisioning error occurred on Pool ${PoolId} because of a resource problem |
| BROKER_PROVISIONING_ERROR_RESYNC_FAILED | Provisioning error occurred for Machine ${MachineName}: Resync operation failed |
| BROKER_PROVISIONING_ERROR_TIMEOUT_CUSTOMIZATION_CLEARED | The previously reported timeout while customizing is no longer present on Pool ${PoolId} |
| BROKER_PROVISIONING_ERROR_TIMEOUT_CUSTOMIZATION_SET | Provisioning error occurred on Pool ${PoolId} because of a timeout while customizing |
| BROKER_PROVISIONING_ERROR_VM_CLONING | Provisioning error occurred for Machine ${MachineName}: Cloning failed for Machine |
| BROKER_PROVISIONING_ERROR_VM_CUSTOMIZATION_ERROR | Provisioning error occurred for Machine ${MachineName}: Customization failed for Machine |
| BROKER_PROVISIONING_ERROR_VM_CUSTOMIZATION_NETWORKING | Provisioning error occurred for Machine ${MachineName}: Customization error due to no network communication between the View agent and Connection Server |
| BROKER_PROVISIONING_ERROR_VM_CUSTOMIZATION_TIMEOUT | Provisioning error occurred for Machine ${MachineName}: Customization operation timed out |
| BROKER_PROVISIONING_NGVC_ERROR_COMPOSER_AGENT_INIT_FAILED | Provisioning error occurred for Machine ${MachineName}: Instant Clone agent initialization failed |
| BROKER_PROVISIONING_POWERON_FAIL_MISSING_HARDWARE_RENDERER | Provisioning error occurred for Pool ${PoolId}, VM ${MachineName} failed to start: A hardware 3D renderer is not available on host ${EsxHostName}. |
| BROKER_PROVISIONING_PUBLISH_IMAGE_FAILED | Image Publish initiated by ${NgvcOp} for Pool ${PoolId} failed for ${Image} |
| BROKER_PROVISIONING_PUBLISH_IMAGE_SUCCESS | Image Publish initiated by ${NgvcOp} for Pool ${PoolId} succeeded for ${Image} |
| BROKER_PROVISIONING_RECOVERY_COMPLETE | Automatic error recovery for Pool ${DesktopId}: recovery complete for Machine ${MachineName} |
| BROKER_PROVISIONING_RECOVERY_FAILED | Automatic error recovery for Pool ${DesktopId}: all recovery attempts failed for Machine ${MachineName} |
| BROKER_PROVISIONING_RECOVERY_START | Automatic error recovery for Pool ${DesktopId}: attempting recovery for Machine ${MachineName} |
| BROKER_PROVISIONING_RECOVERY_VM_DELETE | Automatic error recovery for Pool ${DesktopId}: attempting to delete Machine ${MachineName} |
| BROKER_PROVISIONING_RECOVERY_VM_RESTART | Automatic error recovery for Pool ${DesktopId}: attempting to restart Machine ${MachineName} |
| BROKER_PROVISIONING_RECOVERY_VM_RESYNC | Automatic error recovery for Pool ${DesktopId}: attempting to resync Machine ${MachineName} |
| BROKER_PROVISIONING_SVI_AD_AUTHENTICATION_FAULT | View Composer AD Fault: Failed to authenticate to Active Directory for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_AD_BASE_FAULT | View Composer AD Fault: ${SVIFaultText} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_AD_HOST_UNAVAILABLE_FAULT | View Composer AD Fault: View Composer AD Fault: Active Directory Server is not available for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_AD_OPERATION_ERROR_FAULT | View Composer AD Fault: ${SVIFaultText} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_AD_UNAUTHORIZED_ACCESS_FAULT | View Composer AD Fault: Administrator account used for QuickPrep does not have sufficient permissions for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_CBRC_WARNING_FAULT | View Composer CBRC Warning Fault: ${SVIFaultText} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_CLONE_SNAPSHOT_FAULT | View Composer Fault: Can not perform maintenance work on the vclone that has a snapshot for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_CRYPTO_FAULT | View Composer Fault: Unable to decrypt credentials for component ${ExternalComponent} and configID: ${ConfigID} |
| BROKER_PROVISIONING_SVI_DATABASE_FAULT | View Composer Database Fault: ${SVIFaultText} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_DATASTORE_FULL_FAULT | View Composer Datastore Fault: Not enough disk space for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_DATASTORE_INACCESSIBLE_FAULT | View Composer Datastore Fault: ${SVIFaultText} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_DISK_CUSTOM_FAULT | View Composer DiskFault: ${SVIFaultText} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_ERROR_COMPOSER_AGENT_INIT_FAILED | Provisioning error occurred for Machine ${MachineName}: View Composer agent initialization failed |
| BROKER_PROVISIONING_SVI_ERROR_RECONFIG_FAILED | Provisioning error occurred for Machine ${MachineName}: Reconfigure operation failed |
| BROKER_PROVISIONING_SVI_ERROR_REFIT_FAILED | Provisioning error occurred for Machine ${MachineName}: Refit operation ${SVIOperation} failed |
| BROKER_PROVISIONING_SVI_ERROR_REMOVING_VM | Provisioning error occurred for Machine ${MachineName}: Unable to remove Machine from inventory |
| BROKER_PROVISIONING_SVI_FAULT | View Composer Fault: ${SVIFaultText} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_INTERNAL_FAULT | View Composer Internal Fault: ${SVIFaultText} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_INVALID_CERTIFICATE_FAULT | View Composer Fault: Invalid certificate for ${VCId} due to ${SVIFaultText} |
| BROKER_PROVISIONING_SVI_INVALID_PARAMETER_FAULT | View Composer Fault: ${SVIFaultText} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_INVALID_PARENT_VM_FAULT | View Composer Invalid Parent VM Fault: ${SVIFaultText} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_TOO_MANY_HOSTS_FAULT | View Composer Fault: Resource pool ${ResourcePool} in cluster ${Cluster} has ${HostsCount} hosts, which exceeds the maximum ${MaxHosts} limit for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_UNEXPECTED_VC_FAULT | View Composer Fault: Unexpected VC fault from View Composer ${SVIFaultText} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_VC_AUTHENTICATION_FAULT | View Composer Authentication Fault: Failed to authenticate ${UserName} to VirtualCenter ${VCAddress} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_VC_IN_USE_FAULT | View Composer Fault: ${SVIFaultText} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_VC_INVALID_CLONE_STATE_FAULT | View Composer Fault: The VM is in an INVALID state: ${SVIFaultText}, due to previous unsuccessful deletion attempts. Only deletion is allowed.for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_VC_OBJECT_NOT_FOUND_FAULT | View Composer Fault: Could not find VC object of type ${MoidType} and id ${VmMoid}. Please check the master VM/snapshot or its replica for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_VC_OPERATION_DISABLED_FAULT | View Composer Fault: VC operation is disabled - ${SVIFaultText} for VM ${SVIVMID} |
| BROKER_PROVISIONING_SVI_VC_TASK_TIMEDOUT_FAULT | View Composer Fault: VC operation exceeded the task timeout limit of ${SVIFaultText} mins set by View Composer for VM ${SVIVMID} |
| BROKER_PROVISIONING_UNPUBLISH_IMAGE_FAILED | Image Unublish initiated by ${NgvcOp} for Pool ${PoolId} failed for ${Image} |
| BROKER_PROVISIONING_UNPUBLISH_IMAGE_SUCCESS | Image Unpublish initiated by ${NgvcOp} for Pool ${PoolId} succeeded for ${Image} |
| BROKER_PROVISIONING_VERIFICATION_FAILED_USER_ASSIGNED | Provisioning verification failed for Machine ${MachineName}: User is already assigned to a machine in Pool ${PoolId} |
| BROKER_PROVISIONING_VERIFICATION_FAILED_USER_CANNOT_BE_ASSIGNED | Provisioning verification failed for Machine ${MachineName}: A user cannot be assigned because Pool ${PoolId} is not persistent |
| BROKER_PROVISIONING_VERIFICATION_FAILED_VMNAME_IN_USE | Provisioning verification failed for Machine ${MachineName}: A machine already exists in Pool ${PoolId} with name ${MachineName} |
| BROKER_RADIUS_ALL_SERVER_FAIL | Communication with all RADIUS servers (${PrimaryRadiusServer} and ${SecondaryRadiusServer}) failed. Last tried ${FailedRadiusServer} |
| BROKER_RADIUS_SERVER_FAILOVER | Active RADIUS server has changed to ${ActiveRadiusServer} because communication with ${FailedRadiusServer} failed |
| BROKER_SAML_CERT_EXPIRED | Certificate has expired for SAML Authenticator ${SAMLAuthenticatorLabel} at address ${SAMLAuthenticatorMetadataURL} |
| BROKER_SAML_CERT_EXPIRY_WARNING | Certificate will expire shortly for SAML Authenticator ${SAMLAuthenticatorLabel} at address ${SAMLAuthenticatorMetadataURL} |
| BROKER_SAML_CERT_INVALID | Certificate is invalid for SAML Authenticator ${SAMLAuthenticatorLabel} at address ${SAMLAuthenticatorMetadataURL} |
| BROKER_SECURE_GATEWAY_CERT_EXPIRED | Certificate has expired for Secure Gateway at address ${SecurityServerId} |
| BROKER_SECURE_GATEWAY_CERT_EXPIRY_WARNING | Certificate will expire shortly for Secure Gateway at address ${SecurityServerId} |
| BROKER_SECURE_GATEWAY_CERT_NOTSTARTED | Certificate is not yet valid for Secure Gateway at address ${SecurityServerId} |
| BROKER_SECURE_GATEWAY_CERT_NOTVALID | Certificate is invalid for Secure Gateway at address ${SecurityServerId} |
| BROKER_SECURE_GATEWAY_LEGACY_JMS_PORT_WARNING | Secure Gateway at address ${SecurityServerId} is using legacy JMS port 4001. Please reconfigure your environment to allow TCP traffic on JMS port 4002. |
| BROKER_SECURITY_SERVER_ADD_FAILED | Failed to add security server ${SecurityServerId} |
| BROKER_SECURITY_SERVER_ADD_FAILED_AUTHENTICATION_FAILURE | Failed to add security server ${SecurityServerId}, authentication failure - check pairing password. |
| BROKER_SECURITY_SERVER_ADD_FAILED_INVALID_REQUEST | Failed to add security server ${SecurityServerId}, invalid request. Possible intrusion attempt. |
| BROKER_SECURITY_SERVER_ADD_FAILED_INVALID_REQUEST_NO_SS_NAME | Failed to add unnamed security server, invalid request. Possible intrusion attempt. |
| BROKER_SECURITY_SERVER_ADD_FAILED_PASSWORD_EXPIRED | Failed to add security server ${SecurityServerId}, pairing password expired |
| BROKER_SECURITY_SERVER_ADD_FAILED_PASSWORD_INCORRECT | Failed to add security server ${SecurityServerId}, pairing password incorrect |
| BROKER_SECURITY_SERVER_ADD_FAILED_PASSWORD_NOT_SET | Failed to add security server ${SecurityServerId}, pairing password not set |
| BROKER_SECURITY_SERVER_ADD_FAILED_PASSWORD_NOT_SET_OR_EXPIRED | Failed to add security server ${SecurityServerId}, pairing password not set or expired. |
| BROKER_SECURITY_SERVER_ADDED | Security server ${SecurityServerId} added |
| BROKER_SHADOW_SESSION_REQUEST | User ${UserDisplayName} requested shadow session |
| BROKER_SHADOW_SESSION_REQUEST_FAILED | Unable to launch shadow session for user ${UserDisplayName} |
| BROKER_SHADOW_SESSION_REQUEST_SUCCEEDED | User ${UserDisplayName} successfully launched shadow session |
| BROKER_SMALL_MEMORY | Broker ${BrokerName} has been detected as being configured with a small amount of physical memory. Please refer to the View Installation Guide. |
| BROKER_SVI_ARCHIVE_OS_DISK_FAILED | Failed to archive OS disk to location ${SVIPath} |
| BROKER_SVI_ARCHIVE_OS_DISK_SUCCEEDED | Archived OS disk to location ${SVIPath} |
| BROKER_SVI_ARCHIVE_UDD_FAILED | Failed to archive user data disk ${UserDiskName} to location ${SVIPath} |
| BROKER_SVI_ARCHIVE_UDD_SUCCEEDED | Archived user data disk ${UserDiskName} to location ${SVIPath} |
| BROKER_SVI_ATTACH_UDD_FAILED | Failed to attach user data disk ${UserDiskName} to VM ${SVIVMID} |
| BROKER_SVI_ATTACH_UDD_SUCCEEDED | Attached user data disk ${UserDiskName} to VM ${SVIVMID} |
| BROKER_SVI_CERT_EXPIRED | Certificate has expired for Composer at address ${ComposerId} |
| BROKER_SVI_CERT_EXPIRY_WARNING | Certificate will expire shortly for Composer at address ${ComposerId} |
| BROKER_SVI_CERT_INVALID | Certificate is invalid for Composer at address ${ComposerId} |
| BROKER_SVI_DETACH_UDD_FAILED | Failed to detach user data disk ${UserDiskName} from VM ${SVIVMID} |
| BROKER_SVI_DETACH_UDD_SUCCEEDED | Detached user data disk ${UserDiskName} from VM ${SVIVMID} |
| BROKER_UNAUTHENTICATED_ACCESS_FAILED | Unauthenticated access is failed for user ${UserDisplayName}. |
| BROKER_UNAUTHENTICATED_ACCESS_FAILED_TO_GET_AD_USER_INFO | Unauthenticated access is failed for user ${UserDisplayName}. Failed to get the user info from domain controller. |
| BROKER_USER_AUTHFAILED_ACCOUNT_DISABLED | User ${UserDisplayName} failed to authenticate because the account is disabled |
| BROKER_USER_AUTHFAILED_ACCOUNT_EXPIRED | User ${UserDisplayName} failed to authenticate because the account has expired |
| BROKER_USER_AUTHFAILED_ACCOUNT_LOCKED_OUT | User ${UserDisplayName} failed to authenticate because the account is locked out |
| BROKER_USER_AUTHFAILED_ACCOUNT_RESTRICTION | User ${UserDisplayName} failed to authenticate because of an account restriction |
| BROKER_USER_AUTHFAILED_BAD_USER_PASSWORD | User ${UserDisplayName} failed to authenticate because of a bad username or password |
| BROKER_USER_AUTHFAILED_GENERAL | User ${UserDisplayName} failed to authenticate |
| BROKER_USER_AUTHFAILED_NO_LOGON_SERVERS | User ${UserDisplayName} failed to authenticate because there are no logon servers |
| BROKER_USER_AUTHFAILED_PASSWORD_EXPIRED | User ${UserDisplayName} failed to authenticate because the password has expired |
| BROKER_USER_AUTHFAILED_PASSWORD_MUST_CHANGE | User ${UserDisplayName} failed to authenticate because the password must change |
| BROKER_USER_AUTHFAILED_RADIUS_ACCESS_DENIED | RADIUS access denied for user ${UserDisplayName} |
| BROKER_USER_AUTHFAILED_RADIUS_CHALLENGE_RESPONSE_REJECTED | RADIUS server rejected response to challenge for user ${UserDisplayName} |
| BROKER_USER_AUTHFAILED_RADIUS_WRONG_STATE | RADIUS access denied for user ${UserDisplayName} because of incorrect state |
| BROKER_USER_AUTHFAILED_SAML_ACCESS_DENIED | SAML access denied because of invalid assertion/artifact |
| BROKER_USER_AUTHFAILED_SAML_ACCESS_REQUIRED | SAML access required but not attempted by client |
| BROKER_USER_AUTHFAILED_SECUREID_ACCESS_DENIED | SecurID access denied for user ${UserDisplayName} |
| BROKER_USER_AUTHFAILED_SECUREID_NEWPIN_REJECTED | SecurID access denied for user ${UserDisplayName} because new pin was rejected |
| BROKER_USER_AUTHFAILED_SECUREID_WRONG_NEXTTOKEN | SecurID access denied for user ${UserDisplayName} because wrong next token entered |
| BROKER_USER_AUTHFAILED_SECUREID_WRONG_STATE | SecurID access denied for user ${UserDisplayName} because of incorrect state |
| BROKER_USER_AUTHFAILED_TIME_RESTRICTION | User ${UserDisplayName} failed to authenticate because of a time restriction |
| BROKER_USER_LOCK_SSO | SSO credentials locked for user ${UserDisplayName} |
| BROKER_USER_NOT_AUTHORIZED | User ${UserDisplayName} has authenticated, but is not authorized to perform the operation |
| BROKER_USER_NOT_ENTITLED | User ${UserDisplayName} has authenticated, but is not entitled to any Pools |
| BROKER_USER_POOLS_DISABLED | User ${UserDisplayName} has authenticated, but is only entitled to disabled Pools. |
| BROKER_USER_UNLOCK_SSO | SSO credentials unlocked for user ${UserDisplayName} |
| BROKER_USERCHANGEDPASSWORD | Password for ${UserDisplayName} has been changed by the user |
| BROKER_USERLOGGEDIN | User ${UserDisplayName} has logged in |
| BROKER_USERLOGGEDOUT | User ${UserDisplayName} has logged out |
| BROKER_VC_CERT_EXPIRED | Certificate has expired for vCenter at address ${VCAddress} |
| BROKER_VC_CERT_EXPIRY_WARNING | Certificate will expire shortly for vCenter at address ${VCAddress} |
| BROKER_VC_CERT_INVALID | Certificate is not valid for vCenter at address ${VCAddress} |
| BROKER_VC_DISABLED | vCenter at address ${VCAddress} has been temporarily disabled |
| BROKER_VC_ENABLED | vCenter at address ${VCAddress} has been enabled |
| BROKER_VC_STATUS_CHANGED_CANNOT_LOGIN | Cannot login to vCenter at address ${VCAddress} |
| BROKER_VC_STATUS_CHANGED_DOWN | vCenter at address ${VCAddress} is down |
| BROKER_VC_STATUS_CHANGED_DOWN_INVALID_CERT | vCenter at address ${VCAddress} has an invalid certificate |
| BROKER_VC_STATUS_CHANGED_DOWN_INVALID_CERT_NO_THUMBPRINT | vCenter at address ${VCAddress} has an invalid certificate (not yet accepted) |
| BROKER_VC_STATUS_CHANGED_DOWN_INVALID_CERT_THUMBPRINT_MISMATCH | vCenter at address ${VCAddress} has an invalid certificate (doesn't match previously accepted one) |
| BROKER_VC_STATUS_CHANGED_INVALID_CREDENTIALS | vCenter at address ${VCAddress} has invalid credentials |
| BROKER_VC_STATUS_CHANGED_NOT_YET_CONNECTED | Not yet connected to vCenter at address ${VCAddress} |
| BROKER_VC_STATUS_CHANGED_RECONNECTING | Reconnecting to vCenter at address ${VCAddress} |
| BROKER_VC_STATUS_CHANGED_UNKNOWN | The status of vCenter at address ${VCAddress} is unknown |
| BROKER_VC_STATUS_CHANGED_UP | vCenter at address ${VCAddress} is up |
| ENDPOINT_AMT_DEACTIVATED | AMT is no longer activated on endpoint ${EndpointDisplayName} |
| ENDPOINT_AMT_NOT_ACTIVATED | AMT manageability test failed for endpoint ${EndpointDisplayName} |
| ENDPOINT_AMT_TLS_CONNECT_FAILED | AMT TLS is required and AMT TLS connection failed for endpoint ${EndpointDisplayName} |
| ENDPOINT_REGISTERED | Endpoint ${EndpointDisplayName} registered |
| ENDPOINT_TASK_FAILED | Task ${EndpointTaskDisplayName} failed on endpoint ${EndpointDisplayName} |
| ENDPOINT_TASK_SUCCEEDED | Task ${EndpointTaskDisplayName} succeeded on endpoint ${EndpointDisplayName} |
| GSSAPI_AUTHENTICATOR_CREATED | User ${UserDisplayName} created GSSAPI authenticator |
| GSSAPI_AUTHENTICATOR_DELETED | ${UserDisplayName} deleted GSSAPI authenticator |
| GSSAPI_AUTHENTICATOR_UPDATED | ${UserDisplayName} updated GSSAPI authenticator: (${AttrChangeType}: ${AttrName}   ${AttrValue})" |
| HELPDESK_GET_WS1_ASSIST_AGENT_ID | User ${UserDisplayName} has been granted a Workspace ONE Assist ticket for session ${SessionId} and user ${EndUserDisplayName} |
| HELPDESK_USERLOGGEDIN_BASIC | User ${UserDisplayName} has logged in to Help Desk with credentials |
| HELPDESK_USERLOGGEDIN_SSO | User ${UserDisplayName} has logged in to Help Desk via SSO |
| HELPDESK_USERLOGGEDOFF | User ${UserDisplayName} has logged off from Help Desk |
| HELPDESK_USERLOGIN_BAD_PRIVILEGE | User ${UserDisplayName} does not have sufficient privileges to use Help Desk |
| HELPDESK_USERLOGIN_BASIC_FAILED | User ${UserDisplayName} has failed to authenticate to Help Desk with credentials |
| HELPDESK_USERLOGIN_SSO_FAILED | User ${UserDisplayName} has failed to authenticate to Help Desk via SSO |
| NOTRUST_DOMAIN_BOUND | User ${UserDisplayName} bound No-Trust domain ${Domain} successfully with connection server. |
| NOTRUST_DOMAIN_UNBOUND | User ${UserDisplayName} unbound No-Trust domain ${Domain} successfully from the connection server. |
| NOTRUST_DOMAIN_UPDATED | User ${UserDisplayName} updated No-Trust domain (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| REST_AUTH_LOGIN_FAILURE | User ${UserDisplayName} has failed to login to Horizon Server REST API |
| REST_AUTH_LOGIN_SUCCESS | User ${UserDisplayName} has logged in to Horizon Server REST API |
| REST_AUTH_LOGOUT_SUCCESS | User ${UserDisplayName} has logged out from Horizon Server REST API |
| REST_AUTH_PERMISSION_FAILURE | ${UserDisplayName} does not have sufficient permission to call REST API ${RESTHttpMethodName} operation on ${RESTResourceName}. |
| REST_AUTH_REFRESH_TOKEN_SUCCESS | User ${UserDisplayName} has refreshed access token |
| TEST_RELIABLE | ${Module}: Test ${Severity} level message. Sent with identifier ${TestIdentifier}. |
| TEST_STANDARD | ${Module}: Test ${Severity} level message. Sent with identifier ${TestIdentifier}. |
| TIMING_PROFILER_APPLICATION_LAUNCH | ${ApplicationId} application launch timing profile for ${UserDisplayName}, duration: ${TimingProfilerDuration} |
| TIMING_PROFILER_DESKTOP_LAUNCH | ${DesktopId} desktop launch timing profile for ${UserDisplayName}, duration: ${TimingProfilerDuration} |
| TIMING_PROFILER_DESKTOP_RECONNECT | ${DesktopId} desktop reconnect timing profile for ${UserDisplayName}, duration: ${TimingProfilerDuration} |
| TIMING_PROFILER_GENERIC | ${TimingProfilerType} timing profile, duration: ${TimingProfilerDuration} |
| TIMING_PROFILER_GET_CONFIGURATION | Get configuration timing profile on ${BrokerName}, duration: ${TimingProfilerDuration} |
| TIMING_PROFILER_GET_DESKTOPS | Get desktops timing profile for ${UserDisplayName} on ${BrokerName}, duration: ${TimingProfilerDuration} |
| TIMING_PROFILER_GET_LAUNCH_ITEMS | Get launch items timing profile for ${UserDisplayName} on ${BrokerName}, duration: ${TimingProfilerDuration} |
| TIMING_PROFILER_START_VM | Start VM for ${MachineName} on ${BrokerName}, duration: ${TimingProfilerDuration} |
| TIMING_PROFILER_TUNNEL_CONNECTION | Tunnel connection timing profile for ${UserDisplayName} on ${BrokerName}, duration: ${TimingProfilerDuration} |
| TIMING_PROFILER_USER_AUTHENTICATION | User authentication timing profile for ${UserDisplayName} on ${BrokerName}, duration: ${TimingProfilerDuration} |
| TRANSFER_SERVER_PACKAGE_DISPLACEMENT | Transfer package ${PackageName} was not published on current Transfer Server Repository. |
| TRANSFER_SERVER_PACKAGE_MISSING | Transfer package ${PackageName} was missing on current Transfer Server Repository. |
| TRANSFER_SERVER_PACKAGE_RECOVERY | Transfer package ${PackageName} recovered. |
| TRANSFER_SERVER_PUBLISH_PACKAGE_CANCELLED | Cancelled publish of transfer package ${PackageName} on Transfer Server ${TransferServerDisplay}. |
| TRANSFER_SERVER_PUBLISH_PACKAGE_DISK_SPACE_FAILURE | Failed to publish transfer package ${PackageName} on Transfer Server ${TransferServerDisplay}: insufficient disk space. |
| TRANSFER_SERVER_PUBLISH_PACKAGE_FAILURE | Failed to publish transfer package ${PackageName} on Transfer Server ${TransferServerDisplay}. |
| TRANSFER_SERVER_PUBLISH_PACKAGE_NFC_FAILURE | Failed to publish transfer package ${PackageName} on Transfer Server ${TransferServerDisplay}: an NFC connection attempt failed. |
| TRANSFER_SERVER_PUBLISH_PACKAGE_SUCCESS | Successfully published transfer package ${PackageName} on Transfer Server ${TransferServerDisplay}. |
| TRANSFER_SERVER_REAPER_FAILED | Failed to clean up disk ${DiskPath} on Transfer Server ${TransferServerDisplay}. |
| TRANSFER_SERVER_STATE_CHANGED | Transfer Server ${TransferServerDisplay} state has changed from ${TransferServerOldState} to ${TransferServerNewState} on ${TransferServerStateInput}. |
| VLSI_APPLICATION_CREATE_FAILED | ${UserDisplayName} failed to add Application ${ApplicationDisplayName} |
| VLSI_APPLICATION_CREATED | ${UserDisplayName} added Application ${ApplicationDisplayName} |
| VLSI_APPLICATION_DELETE_FAILED | ${UserDisplayName} failed to remove Application ${ApplicationDisplayName} |
| VLSI_APPLICATION_DELETED | ${UserDisplayName} removed Application ${ApplicationDisplayName} |
| VLSI_APPLICATION_ICON_ASSOCIATION_CREATED | ${UserDisplayName} associated a customized icon with hash ${IconHash} |
| VLSI_APPLICATION_ICON_ASSOCIATION_REMOVE_FAILED | ${UserDisplayName} failed to remove association of customized icon with hash ${IconHash} |
| VLSI_APPLICATION_ICON_ASSOCIATION_REMOVED | ${UserDisplayName} removed association of customized icon with hash ${IconHash} |
| VLSI_APPLICATION_ICON_ASSOCIATION_UPDATE_FAILED | ${UserDisplayName} failed to update association of customized icon with hash ${IconHash} |
| VLSI_APPLICATION_ICON_ASSOCIATION_UPDATED | ${UserDisplayName} updated association of customized icon with hash ${IconHash} |
| VLSI_APPLICATION_ICON_CREATE_ASSOCIATE_FAILED | ${UserDisplayName} failed to create/associate customized icon with hash ${IconHash} |
| VLSI_APPLICATION_ICON_CREATED | ${UserDisplayName} created a customized icon with hash ${IconHash} |
| VLSI_APPLICATION_ICON_CREATED_ASSOCIATED | ${UserDisplayName} created and associated a customized icon with hash ${IconHash} |
| VLSI_APPLICATION_UPDATE_FAILED | ${UserDisplayName} failed to update Application ${ApplicationDisplayName} |
| VLSI_APPLICATION_UPDATED | ${UserDisplayName} updated Application ${ApplicationDisplayName}: (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_APPLICATION_USER_ENTITLEMENT_ADD_FAILED | ${UserDisplayName} failed to entitle ${EntitlementDisplay} to application ${ApplicationDisplayName} |
| VLSI_APPLICATION_USER_ENTITLEMENT_ADDED | ${UserDisplayName} entitled ${EntitlementDisplay} to application ${ApplicationDisplayName} |
| VLSI_APPLICATION_USER_ENTITLEMENT_DELETE_FAILED | ${UserDisplayName} failed to unentitle ${EntitlementDisplay} from application ${ApplicationDisplayName} |
| VLSI_APPLICATION_USER_ENTITLEMENT_DELETED | ${UserDisplayName} unentitled ${EntitlementDisplay} from application ${ApplicationDisplayName} |
| VLSI_CCU_RESET | ${UserDisplayName} reset highest concurrent connection session counter, Highest CCU count: ${CCUCount} |
| VLSI_CEIP_UPDATE_FAILED | User ${UserDisplayName} failed to update CEIP configuration |
| VLSI_CEIP_UPDATED | User ${UserDisplayName} updated CEIP configuration: (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_CERTSSO_CONNECTOR_CREATE_FAILED | ${UserDisplayName} failed to create CertSSO connector ${CertSSOConnectorDisplayName} |
| VLSI_CERTSSO_CONNECTOR_CREATED | ${UserDisplayName} created CertSSO connector ${CertSSOConnectorDisplayName} |
| VLSI_CERTSSO_CONNECTOR_DELETE_FAILED | ${UserDisplayName} failed to delete CertSSO connector ${CertSSOConnectorDisplayName} |
| VLSI_CERTSSO_CONNECTOR_DELETED | ${UserDisplayName} deleted CertSSO connector ${CertSSOConnectorDisplayName} |
| VLSI_CERTSSO_CONNECTOR_UPDATE_FAILED | ${UserDisplayName} failed to update CertSSO connector ${CertSSOConnectorDisplayName} |
| VLSI_CERTSSO_CONNECTOR_UPDATED | ${UserDisplayName} updated CertSSO connector ${CertSSOConnectorDisplayName}: (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_CONNECTION_SERVER_BACKUP_FAILED | ${UserDisplayName} failed to initiate LDAP data backup of connection broker ${BrokerId}. |
| VLSI_CONNECTION_SERVER_BACKUP_INITIATED | ${UserDisplayName} initiated LDAP data backup of connection broker ${BrokerId}. |
| VLSI_CONNECTION_SERVER_MESSAGE_SECURITY_CERTIFICATE_ACTIVATE_FAILED | ${UserDisplayName} failed to activate the pending message security certificate on connection server ${BrokerId}. |
| VLSI_CONNECTION_SERVER_MESSAGE_SECURITY_CERTIFICATE_ACTIVATED | ${UserDisplayName} activated the pending message security certificate on connection server ${BrokerId}. |
| VLSI_CONNECTION_SERVER_MESSAGE_SECURITY_CERTIFICATE_CREATE_FAILED | ${UserDisplayName} failed to create a pending message security certificate on connection server ${BrokerId}. |
| VLSI_CONNECTION_SERVER_MESSAGE_SECURITY_CERTIFICATE_CREATED | ${UserDisplayName} created a pending message security certificate on connection server ${BrokerId}. |
| VLSI_CREATE_MESSAGE_CLIENT | User ${UserDisplayName} has added message client ${MessageClientId} in LDAP |
| VLSI_CREATE_MESSAGE_CLIENT_FAILED | User ${UserDisplayName} failed to add message client in LDAP |
| VLSI_DELETE_MESSAGE_CLIENT | User ${UserDisplayName} has deleted message client ${MessageClientId} in LDAP |
| VLSI_DELETE_MESSAGE_CLIENT_FAILED | User ${UserDisplayName} failed to delete message client ${MessageClientId} in LDAP |
| VLSI_DESKTOP_CANCEL_PUSH_IMAGE_FAILED | ${UserDisplayName} failed to cancel the scheduled push image operation in desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_MACHINE_ADD_FAILED | ${UserDisplayName} failed to add Machine ${MachineName} to Desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_MACHINE_ADDED | ${UserDisplayName} added Machine ${MachineName} to Desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_MACHINE_REMOVE_FAILED | ${UserDisplayName} failed to remove Machine ${MachineName} from Desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_MACHINE_REMOVED | ${UserDisplayName} removed Machine ${MachineName} from Desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_MESSAGE_SECURITY_CERTIFICATE_REFRESH_FAILED | ${UserDisplayName} failed to refresh the message security certificate on desktop ${DesktopDisplayName}. |
| VLSI_DESKTOP_MESSAGE_SECURITY_CERTIFICATE_REFRESHED | ${UserDisplayName} refreshed the message security certificate on desktop ${DesktopDisplayName}. |
| VLSI_DESKTOP_PUSH_IMAGE_CANCELLED | ${UserDisplayName} cancelled the scheduled push image operation in desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_PUSH_IMAGE_SCHEDULED | ${UserDisplayName} scheduled a push image operation in desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_REBALANCE_FAILED | ${UserDisplayName} failed to request a rebalance of ${MachinesCount} machine(s) in desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_REBALANCED | ${UserDisplayName} requested a rebalance of ${MachinesCount} machine(s) in desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_RECOMPOSE_FAILED | ${UserDisplayName} failed to request a recompose of ${MachinesCount} machine(s) in desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_RECOMPOSED | ${UserDisplayName} requested a recompose of ${MachinesCount} machine(s) in desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_REFRESH_FAILED | ${UserDisplayName} failed to request a refresh of ${MachinesCount} machine(s) in desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_REFRESHED | ${UserDisplayName} requested a refresh of ${MachinesCount} machine(s) in desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_SCHEDULE_PUSH_IMAGE_FAILED | ${UserDisplayName} failed to schedule a push image operation in desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_UPDATE_ATTEMPT | ${UserDisplayName} attempted to update Desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_UPDATE_FAILED | ${UserDisplayName} failed to update Desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_UPDATED | ${UserDisplayName} edited Desktop ${DesktopDisplayName} (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_DESKTOP_USER_ENTITLEMENT_ADD_FAILED | ${UserDisplayName} failed to entitle ${EntitlementDisplay} to desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_USER_ENTITLEMENT_ADDED | ${UserDisplayName} entitled ${EntitlementDisplay} to desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_USER_ENTITLEMENT_DELETE_FAILED | ${UserDisplayName} failed to unentitle ${EntitlementDisplay} from desktop ${DesktopDisplayName} |
| VLSI_DESKTOP_USER_ENTITLEMENT_DELETED | ${UserDisplayName} unentitled ${EntitlementDisplay} from desktop ${DesktopDisplayName} |
| VLSI_FARM_CREATE_FAILED | ${UserDisplayName} failed to add Farm ${FarmDisplayName} |
| VLSI_FARM_CREATED | ${UserDisplayName} added Farm ${FarmDisplayName} |
| VLSI_FARM_DELETE_FAILED | ${UserDisplayName} failed to remove Farm ${FarmDisplayName} |
| VLSI_FARM_DELETED | ${UserDisplayName} removed Farm ${FarmDisplayName} |
| VLSI_FARM_MESSAGE_SECURITY_CERTIFICATE_REFRESH_FAILED | ${UserDisplayName} failed to refresh the message security certificate on farm ${FarmDisplayName}. |
| VLSI_FARM_MESSAGE_SECURITY_CERTIFICATE_REFRESHED | ${UserDisplayName} refreshed the message security certificate on farm ${FarmDisplayName}. |
| VLSI_FARM_RDSSERVER_ADD_FAILED | ${UserDisplayName} failed to add RDSServer(s) to Farm ${FarmDisplayName} |
| VLSI_FARM_RDSSERVER_ADDED | ${UserDisplayName} added RDSServer ${RDSServerDisplayName} to Farm ${FarmDisplayName} |
| VLSI_FARM_RDSSERVER_REMOVE_FAILED | ${UserDisplayName} failed to remove RDSServer(s) from Farm ${FarmDisplayName} |
| VLSI_FARM_RDSSERVER_REMOVED | ${UserDisplayName} removed RDSServer ${RDSServerDisplayName} from Farm ${FarmDisplayName} |
| VLSI_FARM_RECOMPOSE_FAILED | ${UserDisplayName} failed to request a recompose of ${MachinesCount} RDS Server(s) in Farm ${FarmDisplayName} |
| VLSI_FARM_RECOMPOSED | ${UserDisplayName} requested a recompose of ${MachinesCount} RDS Server(s) in Farm ${FarmDisplayName} |
| VLSI_FARM_SCHEDULED_MAINTENANCE_CANCEL_FAILED | ${UserDisplayName} failed to cancel the scheduled maintenance operation in farm ${FarmDisplayName} |
| VLSI_FARM_SCHEDULED_MAINTENANCE_CANCELLED | ${UserDisplayName} cancelled the scheduled maintenance operation in farm ${FarmDisplayName} |
| VLSI_FARM_SCHEDULED_MAINTENANCE_CREATE_FAILED | ${UserDisplayName} failed to schedule a maintenance operation in farm ${FarmDisplayName} |
| VLSI_FARM_SCHEDULED_MAINTENANCE_CREATED | ${UserDisplayName} scheduled a maintenance operation in farm ${FarmDisplayName} |
| VLSI_FARM_UPDATE_FAILED | ${UserDisplayName} failed to update Farm ${FarmDisplayName} |
| VLSI_FARM_UPDATED | ${UserDisplayName} updated Farm ${FarmDisplayName}: (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_FEDERATED_DESKTOP_SESSION_DISCONNECT_REQUEST_SEND_FAILED | ${UserDisplayName} failed to send a session disconnect request to pod ${PodName} for session with id ${SessionId} |
| VLSI_FEDERATED_DESKTOP_SESSION_DISCONNECT_REQUEST_SENT | ${UserDisplayName} has sent a session disconnect request to pod ${PodName} for session with id ${SessionId} |
| VLSI_FEDERATED_DESKTOP_SESSION_LOGOFF_REQUEST_SEND_FAILED | ${UserDisplayName} failed to send a session logoff request to pod ${PodName} for session with id ${SessionId} |
| VLSI_FEDERATED_DESKTOP_SESSION_LOGOFF_REQUEST_SENT | ${UserDisplayName} has sent a session logoff request to pod ${PodName} for session with id ${SessionId} |
| VLSI_FEDERATED_DESKTOP_SESSION_RESET_REQUEST_SEND_FAILED | ${UserDisplayName} failed to send a session reset request to pod ${PodName} for session with id ${SessionId} |
| VLSI_FEDERATED_DESKTOP_SESSION_RESET_REQUEST_SENT | ${UserDisplayName} has sent a session reset request to pod ${PodName} for session with id ${SessionId} |
| VLSI_FEDERATED_DESKTOP_SESSION_RESTART_REQUEST_SEND_FAILED | ${UserDisplayName} failed to send a session restart request to pod ${PodName} for session with id ${SessionId} |
| VLSI_FEDERATED_DESKTOP_SESSION_RESTART_REQUEST_SENT | ${UserDisplayName} has sent a session restart request to pod ${PodName} for session with id ${SessionId} |
| VLSI_FEDERATED_DESKTOP_SESSION_SEND_MESSAGE_REQUEST_SEND_FAILED | ${UserDisplayName} failed to send a session send message request to pod ${PodName} for session with id ${SessionId} with message (${SessionMessage}) |
| VLSI_FEDERATED_DESKTOP_SESSION_SEND_MESSAGE_REQUEST_SENT | ${UserDisplayName} has sent a session send message request to pod ${PodName} for session with id ${SessionId} with message (${SessionMessage}) |
| VLSI_FEDERATED_KILLAPPLICATION_FAILED | User ${UserDisplayName} has failed to kill remote application ${RemoteApplicationDescription} (APPID ${RemoteApplicationId}) in session ${SessionId} in pod ${PodName} for user ${EndUserDisplayName} |
| VLSI_FEDERATED_KILLEDAPPLICATION | User ${UserDisplayName} attempted to kill remote application ${RemoteApplicationDescription} (APPID ${RemoteApplicationId}) in session ${SessionId} in pod ${PodName} for user ${EndUserDisplayName} |
| VLSI_FEDERATED_KILLEDPROCESS | User ${UserDisplayName} has killed remote process ${ProcessName}(PID ${ProcessId}) in session ${SessionId} in pod ${PodName} for user ${EndUserDisplayName} |
| VLSI_FEDERATED_KILLPROCESS_FAILED | User ${UserDisplayName} has failed to kill remote process ${ProcessName}(PID ${ProcessId}) in session ${SessionId} in pod ${PodName} |
| VLSI_FEDERATED_REMOTE_ASSISTANCE | User ${UserDisplayName} has successfully requested a remote assistance ticket from pod ${PodName} for session ${SessionId} and user ${EndUserDisplayName} |
| VLSI_FEDERATED_REMOTE_ASSISTANCE_FAILED | User ${UserDisplayName} has failed to get a remote assistance ticket from pod ${PodName} for session ${SessionId} |
| VLSI_GAE_ADD_FAILED | ${UserDisplayName} failed to create global application entitlement: ${GlobalEntitlementName}. |
| VLSI_GAE_ADDED | ${UserDisplayName} created global application entitlement: ${GlobalEntitlementName}. |
| VLSI_GAE_CHANGE_FAILED | ${UserDisplayName} failed to update global application entitlement: ${GlobalEntitlementName}. |
| VLSI_GAE_CHANGED | ${UserDisplayName} updated: (${AttrChangeType}: ${AttrName}   ${AttrValue}) for global application entitlement: ${GlobalEntitlementName}. |
| VLSI_GAE_DELETE_FAILED | ${UserDisplayName} failed to delete global application entitlement: ${GlobalEntitlementName}. |
| VLSI_GAE_DELETED | ${UserDisplayName} deleted global application entitlement: ${GlobalEntitlementName}. |
| VLSI_GAE_LOCAL_POOL_ADDED | ${UserDisplayName} added local pool ${ApplicationDisplayName} to global application entitlement ${GlobalEntitlementName} |
| VLSI_GAE_LOCAL_POOL_DELETED | ${UserDisplayName} deleted local pool ${ApplicationDisplayName} from global application entitlement ${GlobalEntitlementName} |
| VLSI_GAE_USER_ENTITLEMENT_ADD_FAILED | ${UserDisplayName} failed to entitle ${EntitlementDisplay} to global application entitlement ${GlobalEntitlementName} |
| VLSI_GAE_USER_ENTITLEMENT_ADDED | ${UserDisplayName} entitled ${EntitlementDisplay} to global application entitlement ${GlobalEntitlementName} |
| VLSI_GAE_USER_ENTITLEMENT_DELETE_FAILED | ${UserDisplayName} failed to unentitle ${EntitlementDisplay} from global application entitlement ${GlobalEntitlementName} |
| VLSI_GAE_USER_ENTITLEMENT_DELETED | ${UserDisplayName} unentitled ${EntitlementDisplay} from global application entitlement ${GlobalEntitlementName} |
| VLSI_GATEWAY_REGISTERATION | User ${UserDisplayName} has registered ${GatewayDisplayName} in LDAP successfully |
| VLSI_GATEWAY_REGISTERATION_FAILED | User ${UserDisplayName} failed to register ${GatewayDisplayName} in LDAP |
| VLSI_GATEWAY_UNREGISTERATION | User ${UserDisplayName} has unregistered ${GatewayDisplayName} in LDAP successfully |
| VLSI_GATEWAY_UNREGISTERATION_FAILED | User ${UserDisplayName} failed to unregister ${GatewayDisplayName} in LDAP |
| VLSI_GE_ADD_FAILED | ${UserDisplayName} failed to create global entitlement: ${GlobalEntitlementName}. |
| VLSI_GE_ADDED | ${UserDisplayName} created global entitlement: ${GlobalEntitlementName}. |
| VLSI_GE_CHANGE_FAILED | ${UserDisplayName} failed to update global entitlement: ${GlobalEntitlementName}. |
| VLSI_GE_CHANGED | ${UserDisplayName} updated: (${AttrChangeType}: ${AttrName}   ${AttrValue}) for global entitlement: ${GlobalEntitlementName}. |
| VLSI_GE_DELETE_FAILED | ${UserDisplayName} failed to delete global entitlement: ${GlobalEntitlementName}. |
| VLSI_GE_DELETED | ${UserDisplayName} deleted global entitlement: ${GlobalEntitlementName}. |
| VLSI_GE_LOCAL_POOL_ADDED | ${UserDisplayName} added local pool ${DesktopDisplayName} to global entitlement ${GlobalEntitlementName} |
| VLSI_GE_LOCAL_POOL_DELETED | ${UserDisplayName} deleted local pool ${DesktopDisplayName} from global entitlement ${GlobalEntitlementName} |
| VLSI_GE_USER_ENTITLEMENT_ADD_FAILED | ${UserDisplayName} failed to entitle ${EntitlementDisplay} to global entitlement ${GlobalEntitlementName} |
| VLSI_GE_USER_ENTITLEMENT_ADDED | ${UserDisplayName} entitled ${EntitlementDisplay} to global entitlement ${GlobalEntitlementName} |
| VLSI_GE_USER_ENTITLEMENT_DELETE_FAILED | ${UserDisplayName} failed to unentitle ${EntitlementDisplay} from global entitlement ${GlobalEntitlementName} |
| VLSI_GE_USER_ENTITLEMENT_DELETED | ${UserDisplayName} unentitled ${EntitlementDisplay} from global entitlement ${GlobalEntitlementName} |
| VLSI_GLOBAL_POLICY_UPDATED | ${UserDisplayName} updated global policy (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_GLOBAL_SETTINGS_UPDATE_FAILED | User ${UserDisplayName} failed to update global settings |
| VLSI_GLOBAL_SETTINGS_UPDATED | User ${UserDisplayName} updated global settings: (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_IM_ASSET_ADD_FAILED | ${UserDisplayName} failed to add Image Management Asset |
| VLSI_IM_ASSET_ADDED | ${UserDisplayName} added Image Management Asset ${ImageManagementAssetId} |
| VLSI_IM_ASSET_DELETE_FAILED | ${UserDisplayName} failed to delete Image Management Asset ${ImageManagementAssetId} |
| VLSI_IM_ASSET_DELETED | ${UserDisplayName} deleted Image Management Asset ${ImageManagementAssetId} |
| VLSI_IM_ASSET_UPDATE_FAILED | ${UserDisplayName} failed to update Image Management Asset ${ImageManagementAssetId} |
| VLSI_IM_ASSET_UPDATED | ${UserDisplayName} updated Image Management Asset ${ImageManagementAssetId} |
| VLSI_IM_STREAM_ADD_FAILED | ${UserDisplayName} failed to add Image Management Stream |
| VLSI_IM_STREAM_ADDED | ${UserDisplayName} added Image Management Stream ${ImageManagementStreamId} |
| VLSI_IM_STREAM_DELETE_FAILED | ${UserDisplayName} failed to delete Image Management Stream ${ImageManagementStreamId} |
| VLSI_IM_STREAM_DELETED | ${UserDisplayName} deleted Image Management Stream ${ImageManagementStreamId} |
| VLSI_IM_STREAM_UPDATE_FAILED | ${UserDisplayName} failed to update Image Management Stream ${ImageManagementStreamId} |
| VLSI_IM_STREAM_UPDATED | ${UserDisplayName} updated Image Management Stream ${ImageManagementStreamId} |
| VLSI_IM_TAG_ADD_FAILED | ${UserDisplayName} failed to add Image Management Tag |
| VLSI_IM_TAG_ADDED | ${UserDisplayName} added Image Management Tag ${ImageManagementTagId} |
| VLSI_IM_TAG_DELETE_FAILED | ${UserDisplayName} failed to delete Image Management Tag ${ImageManagementTagId} |
| VLSI_IM_TAG_DELETED | ${UserDisplayName} deleted Image Management Tag ${ImageManagementTagId} |
| VLSI_IM_TAG_UPDATE_FAILED | ${UserDisplayName} failed to update Image Management Tag ${ImageManagementTagId} |
| VLSI_IM_TAG_UPDATED | ${UserDisplayName} updated Image Management Tag ${ImageManagementTagId} |
| VLSI_IM_VERSION_ADD_FAILED | ${UserDisplayName} failed to add Image Management Version |
| VLSI_IM_VERSION_ADDED | ${UserDisplayName} added Image Management Version ${ImageManagementVersionId} |
| VLSI_IM_VERSION_DELETE_FAILED | ${UserDisplayName} failed to delete Image Management Version ${ImageManagementVersionId} |
| VLSI_IM_VERSION_DELETED | ${UserDisplayName} deleted Image Management Version ${ImageManagementVersionId} |
| VLSI_IM_VERSION_UPDATE_FAILED | ${UserDisplayName} failed to update Image Management Version ${ImageManagementVersionId} |
| VLSI_IM_VERSION_UPDATED | ${UserDisplayName} updated Image Management Version ${ImageManagementVersionId} |
| VLSI_INSTANT_CLONE_ADMIN_CREATE_FAILED | ${UserDisplayName} failed to create Instant Clone Engine ClonePrep domain ${InstantCloneDomainAdminFQDN} with admin ${InstantCloneDomainAdminName} |
| VLSI_INSTANT_CLONE_ADMIN_CREATED | ${UserDisplayName} created Instant Clone Engine ClonePrep domain ${InstantCloneDomainAdminFQDN} with admin ${InstantCloneDomainAdminName} |
| VLSI_INSTANT_CLONE_ADMIN_DELETE_FAILED | ${UserDisplayName} failed to delete Instant Clone Engine ClonePrep domain ${InstantCloneDomainAdminFQDN} with admin ${InstantCloneDomainAdminName} |
| VLSI_INSTANT_CLONE_ADMIN_DELETED | ${UserDisplayName} deleted Instant Clone Engine ClonePrep domain ${InstantCloneDomainAdminFQDN} with admin ${InstantCloneDomainAdminName} |
| VLSI_INSTANT_CLONE_ADMIN_UPDATE_FAILED | ${UserDisplayName} failed to update Instant Clone Engine ClonePrep domain ${InstantCloneDomainAdminFQDN} with admin ${InstantCloneDomainAdminName} |
| VLSI_INSTANT_CLONE_ADMIN_UPDATED | ${UserDisplayName} updated Instant Clone Engine ClonePrep domain ${InstantCloneDomainAdminFQDN} with admin ${InstantCloneDomainAdminName} |
| VLSI_INSUFFICIENT_PERMISSION | ${UserDisplayName} does not have sufficient permission to invoke ${ViewApiMethodName} operation against ${ViewApiServiceName} service. |
| VLSI_JWT_TOKEN_GENERATED | Successfully generated JWT token for ${UserDisplayName} |
| VLSI_JWT_TOKEN_GENERATION_FAILED | Failed to generate JWT token for ${UserDisplayName} |
| VLSI_KILLAPPLICATION_FAILED | User ${UserDisplayName} has failed to kill remote application ${RemoteApplicationDescription} (APPID ${RemoteApplicationId}) in session ${SessionId} for user ${EndUserDisplayName} |
| VLSI_KILLEDAPPLICATION | User ${UserDisplayName} attempted to kill remote application ${RemoteApplicationDescription} (APPID ${RemoteApplicationId}) in session ${SessionId} for user ${EndUserDisplayName} |
| VLSI_KILLEDPROCESS | User ${UserDisplayName} has killed remote process ${ProcessName}(PID ${ProcessId}) in session ${SessionId} for user ${EndUserDisplayName} |
| VLSI_KILLPROCESS_FAILED | User ${UserDisplayName} has failed to kill remote process ${ProcessName}(PID ${ProcessId}) in session ${SessionId} for user ${EndUserDisplayName} |
| VLSI_LOG_COLLECTION_ABORT_TASK_SUCCESS | ${UserDisplayName} initiated log abort on ${LogComponentType} ${LogComponentName} |
| VLSI_LOG_COLLECTION_DOWNLOAD_TASK_SUCCESS | ${UserDisplayName} requested log download URL on ${LogComponentType} ${LogComponentName} |
| VLSI_LOG_COLLECTION_INITIATE_TASK_SUCCESS | ${UserDisplayName} initiated log collection on ${LogComponentType} ${LogComponentName} |
| VLSI_LOG_COLLECTION_PURGE_TASK_SUCCESS | ${UserDisplayName} initiated log purge on ${LogComponentType} ${LogComponentName} |
| VLSI_LOGIN_FAIL | User login attempt has failed to authenticate to View Administrator |
| VLSI_MACHINE_DELETE_FAILED | ${UserDisplayName} failed to delete Machine ${MachineName} |
| VLSI_MACHINE_DELETED | ${UserDisplayName} deleted Machine ${MachineName} |
| VLSI_MACHINE_MAINTENANCE | ${UserDisplayName} performed maintenance operation on Machine ${MachineName} |
| VLSI_MACHINE_MAINTENANCE_FAILED | ${UserDisplayName} failed to perform maintenance operation on Machine ${MachineName} |
| VLSI_MACHINE_MESSAGE_SECURITY_CERTIFICATE_REFRESH_FAILED | ${UserDisplayName} failed to refresh the message security certificate on machine ${MachineName}. |
| VLSI_MACHINE_MESSAGE_SECURITY_CERTIFICATE_REFRESHED | ${UserDisplayName} refreshed the message security certificate on machine ${MachineName}. |
| VLSI_MACHINE_REBALANCE_FAILED | ${UserDisplayName} failed to request a rebalance of machine ${MachineName} in desktop ${DesktopDisplayName} |
| VLSI_MACHINE_REBALANCED | ${UserDisplayName} requested a rebalance of machine ${MachineName} in desktop ${DesktopDisplayName} |
| VLSI_MACHINE_REBUILD | ${UserDisplayName} rebuilt Machine ${MachineName} |
| VLSI_MACHINE_REBUILD_FAILED | ${UserDisplayName} failed to rebuild Machine ${MachineName} |
| VLSI_MACHINE_RECOMPOSE_FAILED | ${UserDisplayName} failed to request a recompose of machine ${MachineName} in desktop ${DesktopDisplayName} |
| VLSI_MACHINE_RECOMPOSED | ${UserDisplayName} requested a recompose of machine ${MachineName} in desktop ${DesktopDisplayName} |
| VLSI_MACHINE_RECOVERY_REQUEST_FAILED | ${UserDisplayName} failed to mark Machine ${MachineName} for recovery |
| VLSI_MACHINE_RECOVERY_REQUESTED | ${UserDisplayName} marked Machine ${MachineName} for recovery |
| VLSI_MACHINE_REFRESH_FAILED | ${UserDisplayName} failed to request a refresh of machine ${MachineName} in desktop ${DesktopDisplayName} |
| VLSI_MACHINE_REFRESHED | ${UserDisplayName} requested a refresh of machine ${MachineName} in desktop ${DesktopDisplayName} |
| VLSI_MACHINE_REGISTERED | ${UserDisplayName} registered Machine ${MachineName} |
| VLSI_MACHINE_REGISTRATION_FAILED | ${UserDisplayName} failed to register Machine ${MachineName} |
| VLSI_MACHINE_RESET | ${UserDisplayName} reset Machine ${MachineName} |
| VLSI_MACHINE_RESET_FAILED | ${UserDisplayName} failed to reset Machine ${MachineName} |
| VLSI_MACHINE_RESTART | ${UserDisplayName} restarted Machine ${MachineName} |
| VLSI_MACHINE_RESTART_FAILED | ${UserDisplayName} failed to restart Machine ${MachineName} |
| VLSI_MACHINE_UPDATE_FAILED | ${UserDisplayName} failed to update Machine ${MachineName} |
| VLSI_MACHINE_UPDATED | ${UserDisplayName} updated Machine ${MachineName}: (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_NETWORK_PROXY_CONFIGURATION_UPDATE_FAILED | User ${UserDisplayName} has failed to update Network Proxy Configuration |
| VLSI_NETWORK_PROXY_CONFIGURATION_UPDATED | User ${UserDisplayName} has updated Network Proxy Configuration: (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_NU_RESET | ${UserDisplayName} reset named user session counter, Current NU Count: ${NUCount} |
| VLSI_PERSISTENT_DISK_ATTACH_FAILED | ${UserDisplayName} failed to request the attachment of persistent disk ${UserDiskName} to machine ${MachineName} |
| VLSI_PERSISTENT_DISK_ATTACHED | ${UserDisplayName} requested the attachment of persistent disk ${UserDiskName} to machine ${MachineName} |
| VLSI_PERSISTENT_DISK_CREATE_FAILED | ${UserDisplayName} failed to create persistent disk ${UserDiskName} |
| VLSI_PERSISTENT_DISK_CREATED | ${UserDisplayName} created persistent disk ${UserDiskName} |
| VLSI_PERSISTENT_DISK_DELETE_FAILED | ${UserDisplayName} failed to delete persistent disk ${UserDiskName} |
| VLSI_PERSISTENT_DISK_DELETED | ${UserDisplayName} deleted persistent disk ${UserDiskName} |
| VLSI_PERSISTENT_DISK_DETACH_FAILED | ${UserDisplayName} failed to request the detachment of persistent disk ${UserDiskName} from machine ${MachineName} |
| VLSI_PERSISTENT_DISK_DETACHED | ${UserDisplayName} requested the detachment of persistent disk ${UserDiskName} from machine ${MachineName} |
| VLSI_PERSISTENT_DISK_RECREATE_MACHINE | ${UserDisplayName} requested the recreation of a machine for persistent disk ${UserDiskName} in desktop ${DesktopDisplayName} |
| VLSI_PERSISTENT_DISK_RECREATE_MACHINE_FAILED | ${UserDisplayName} failed to request the recreation of a machine for persistent disk ${UserDiskName} in desktop ${DesktopDisplayName} |
| VLSI_PERSISTENT_DISK_REPLACE_FAILED | ${UserDisplayName} failed to request the replacement of persistent disk ${UserDiskName} from machine ${MachineName} |
| VLSI_PERSISTENT_DISK_REPLACED | ${UserDisplayName} requested the replacement of persistent disk ${UserDiskName} from machine ${MachineName} |
| VLSI_PERSISTENT_DISK_UPDATE_FAILED | ${UserDisplayName} failed to update persistent disk ${UserDiskName} |
| VLSI_PERSISTENT_DISK_UPDATED | ${UserDisplayName} updated persistent disk ${UserDiskName}: (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_POD_ENDPOINT_CERTIFICATE_ACTIVATION_FAILURE | ${UserDisplayName} fail to activate the pending certificate on pod endpoint ${PodEndpointName}. |
| VLSI_POD_ENDPOINT_CERTIFICATE_ACTIVATION_SUCCESS | ${UserDisplayName} activated the pending certificate on pod endpoint ${PodEndpointName}. |
| VLSI_POD_ENDPOINT_CERTIFICATE_CREATE_FAILURE | ${UserDisplayName} failed to create a pending certificate on pod endpoint ${PodEndpointName}. |
| VLSI_POD_ENDPOINT_CERTIFICATE_CREATE_SUCCESS | ${UserDisplayName} created a pending certificate on pod endpoint ${PodEndpointName}. |
| VLSI_POD_FEDERATION_CONCURRENT_OP | Failed to complete ${ViewApiMethodName} operation against ${ViewApiServiceName} service as there is already an active ${ConcurrentOpName} operation. |
| VLSI_POD_FEDERATION_EJECT_FAILURE | Failed to eject pod ${PodName} from PodFederation. |
| VLSI_POD_FEDERATION_EJECT_SUCCESS | Successfully ejected pod ${PodName} from PodFederation. |
| VLSI_POD_FEDERATION_JOIN_FAILURE | Failed to join PodFederation via remote server ${RemotePodEndpoint}. |
| VLSI_POD_FEDERATION_JOIN_SUCCESS | Successfully joined PodFederation via remote server ${RemotePodEndpoint}. |
| VLSI_POD_FEDERATION_OP_FAILURE | Failed to complete ${ViewApiMethodName} operation against ${ViewApiServiceName} service. |
| VLSI_POD_FEDERATION_OP_SUCCESS | Successfully completed ${ViewApiMethodName} operation against ${ViewApiServiceName} service. |
| VLSI_POD_FEDERATION_TASK_TRIGGERED | Started ${ViewApiMethodName} operation against ${ViewApiServiceName} service. |
| VLSI_POD_UPDATE_FAILURE | ${UserDisplayName} failed to update pod: ${PodName}. |
| VLSI_POD_UPDATE_SUCCESS | ${UserDisplayName} updated: (${AttrChangeType}: ${AttrName}   ${AttrValue}) for pod: ${PodName}. |
| VLSI_POOL_POLICY_UPDATED | ${UserDisplayName} updated pool ${DesktopId} policy (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_RADIUS_AUTHENTICATOR_CREATE_FAILED | ${UserDisplayName} failed to create RADIUS authenticator ${RADIUSAuthenticatorName} |
| VLSI_RADIUS_AUTHENTICATOR_CREATED | ${UserDisplayName} created RADIUS authenticator ${RADIUSAuthenticatorName} |
| VLSI_RADIUS_AUTHENTICATOR_DELETE_FAILED | ${UserDisplayName} failed to delete RADIUS authenticator ${RADIUSAuthenticatorName} |
| VLSI_RADIUS_AUTHENTICATOR_DELETED | ${UserDisplayName} deleted RADIUS authenticator ${RADIUSAuthenticatorName} |
| VLSI_RADIUS_AUTHENTICATOR_UPDATE_FAILED | ${UserDisplayName} failed to update RADIUS authenticator ${RADIUSAuthenticatorName} |
| VLSI_RADIUS_AUTHENTICATOR_UPDATED | ${UserDisplayName} updated RADIUS authenticator ${RADIUSAuthenticatorName}: (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_RCX_CLIENT_REGISTER_FAILED | Failed to register RCX client ${RCXClientName} |
| VLSI_RCX_CLIENT_REGISTERED | Successfully registered RCX client ${RCXClientName} |
| VLSI_RCX_CLIENT_UNREGISTER_FAILED | Failed to unregister RCX client ${RCXClientName} |
| VLSI_RCX_CLIENT_UNREGISTERED | Successfully unregistered RCX client ${RCXClientName} |
| VLSI_RCX_CLIENT_UPDATE_FAILED | Failed to update RCX client ${RCXClientName} |
| VLSI_RCX_CLIENT_UPDATED | Successfully updated RCX client ${RCXClientName}: (${AttrChangeType}: ${AttrName}   ${AttrValue} |
| VLSI_RDS_SERVER_MESSAGE_SECURITY_CERTIFICATE_REFRESH_FAILED | ${UserDisplayName} failed to refresh the message security certificate on RDS Server ${RDSServerDisplayName}. |
| VLSI_RDS_SERVER_MESSAGE_SECURITY_CERTIFICATE_REFRESHED | ${UserDisplayName} refreshed the message security certificate on RDS Server ${RDSServerDisplayName}. |
| VLSI_RDSSERVER_DELETE_FAILED | ${UserDisplayName} failed to remove RDSServer ${RDSServerDisplayName} |
| VLSI_RDSSERVER_DELETED | ${UserDisplayName} removed RDSServer ${RDSServerDisplayName} |
| VLSI_RDSSERVER_RECOMPOSE_FAILED | ${UserDisplayName} failed to request a recompose of RDSServer ${RDSServerDisplayName} in Farm ${FarmDisplayName} |
| VLSI_RDSSERVER_RECOMPOSED | ${UserDisplayName} requested a recompose of RDSServer ${RDSServerDisplayName} in Farm ${FarmDisplayName} |
| VLSI_RDSSERVER_RECOVERY_REQUEST_FAILED | ${UserDisplayName} failed to mark RDSServer ${RDSServerDisplayName} for recovery |
| VLSI_RDSSERVER_RECOVERY_REQUESTED | ${UserDisplayName} marked RDSServer ${RDSServerDisplayName} for recovery |
| VLSI_RDSSERVER_REGISTERED | ${UserDisplayName} registered RDSServer ${RDSServerDisplayName} |
| VLSI_RDSSERVER_REGISTRATION_FAILED | ${UserDisplayName} failed to register RDSServer ${RDSServerDisplayName} |
| VLSI_RDSSERVER_UPDATE_FAILED | ${UserDisplayName} failed to update RDSServer ${RDSServerDisplayName} |
| VLSI_RDSSERVER_UPDATED | ${UserDisplayName} updated RDSServer ${RDSServerDisplayName}: (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_REGISTERED_PHYSICAL_MACHINE_DELETE_FAILED | ${UserDisplayName} failed to delete RegisteredPhysicalMachine ${MachineName} |
| VLSI_REGISTERED_PHYSICAL_MACHINE_DELETED | ${UserDisplayName} deleted RegisteredPhysicalMachine ${MachineName} |
| VLSI_REMOTE_ASSISTANCE | User ${UserDisplayName} has successfully requested a remote assistance ticket for session ${SessionId} and user ${EndUserDisplayName} |
| VLSI_REMOTE_ASSISTANCE_FAILED | User ${UserDisplayName} has failed to get a remote assistance ticket for session ${SessionId} and user ${EndUserDisplayName} |
| VLSI_SAML_AUTHENTICATOR_CREATE_FAILED | ${UserDisplayName} failed to create SAML authenticator ${SAMLAuthenticatorLabel} |
| VLSI_SAML_AUTHENTICATOR_CREATED | ${UserDisplayName} created SAML authenticator ${SAMLAuthenticatorLabel} |
| VLSI_SAML_AUTHENTICATOR_DELETE_FAILED | ${UserDisplayName} failed to delete SAML authenticator ${SAMLAuthenticatorLabel} |
| VLSI_SAML_AUTHENTICATOR_DELETED | ${UserDisplayName} deleted SAML authenticator ${SAMLAuthenticatorLabel} |
| VLSI_SAML_AUTHENTICATOR_UPDATE_FAILED | ${UserDisplayName} failed to update SAML authenticator ${SAMLAuthenticatorLabel} |
| VLSI_SAML_AUTHENTICATOR_UPDATED | ${UserDisplayName} updated SAML authenticator ${SAMLAuthenticatorLabel}: (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_SECONDARY_CREDENTIALS_CREATE_FAILED | User ${UserDisplayName} failed to create secondary credentials for owner: ${Owner}, domain: ${Domain}, username: ${UserName} because ${FailureReason} |
| VLSI_SECONDARY_CREDENTIALS_CREATED | User ${UserDisplayName} created secondary credentials for owner: ${Owner}, domain: ${Domain}, username: ${UserName} |
| VLSI_SECONDARY_CREDENTIALS_DELETE_FAILED | User ${UserDisplayName} failed to delete secondary credentials for owner: ${Owner}, domain: ${Domain}, username: ${UserName} because ${FailureReason} |
| VLSI_SECONDARY_CREDENTIALS_DELETED | User ${UserDisplayName} deleted secondary credentials for owner: ${Owner}, domain: ${Domain}, username: ${UserName} |
| VLSI_SECONDARY_CREDENTIALS_UPDATE_FAILED | User ${UserDisplayName} failed to update secondary credentials for owner: ${Owner}, domain: ${Domain}, username: ${UserName} because ${FailureReason} |
| VLSI_SECONDARY_CREDENTIALS_UPDATED | User ${UserDisplayName} updated secondary credentials for owner: ${Owner}, domain: ${Domain}, username: ${UserName} |
| VLSI_SECURITY_SERVER_MESSAGE_SECURITY_CERTIFICATE_REFRESH_FAILED | ${UserDisplayName} failed to refresh the message security certificate on security server ${SecurityServerId}. |
| VLSI_SECURITY_SERVER_MESSAGE_SECURITY_CERTIFICATE_REFRESHED | ${UserDisplayName} refreshed the message security certificate on security server ${SecurityServerId}. |
| VLSI_SET_LICENSE_MODE | User ${UserDisplayName} has updated the license mode to ${NewLicenseMode} |
| VLSI_SET_LICENSE_MODE_FAILED | User ${UserDisplayName} failed to update the license mode to ${NewLicenseMode} because ${FailureReason} |
| VLSI_SET_SUBSCRIPTION_LICENSE_DATA | User ${UserDisplayName} has successfully updated the license data in LDAP |
| VLSI_SET_SUBSCRIPTION_LICENSE_DATA_FAILED | User ${UserDisplayName} failed to updated the license data in LDAP because ${FailureReason} |
| VLSI_SET_SUBSCRIPTION_LICENSE_DATA_KEY | User ${UserDisplayName} has updated subscription license data key in LDAP |
| VLSI_SET_SUBSCRIPTION_LICENSE_DATA_KEY_FAILED | User ${UserDisplayName} failed to update subscription license data key in LDAP because ${FailureReason} |
| VLSI_SITE_CREATE_FAILURE | ${UserDisplayName} failed to create site: ${SiteName}. |
| VLSI_SITE_CREATE_SUCCESS | ${UserDisplayName} created site: ${SiteName}. |
| VLSI_SITE_DELETE_FAILURE | ${UserDisplayName} failed to delete site: ${SiteName}. |
| VLSI_SITE_DELETE_SUCCESS | ${UserDisplayName} deleted site: ${SiteName}. |
| VLSI_SITE_UPDATE_FAILURE | ${UserDisplayName} failed to update site: ${SiteName}. |
| VLSI_SITE_UPDATE_SUCCESS | ${UserDisplayName} updated: (${AttrChangeType}: ${AttrName}   ${AttrValue}) for site: ${SiteName}. |
| VLSI_UNAUTHENTICATED_ACCESS_USER_CREATED | ${UserDisplayName} created Unauthenticated Access User ${UserName} |
| VLSI_UNAUTHENTICATED_ACCESS_USER_CREATION_FAILED | ${UserDisplayName} failed to create Unauthenticated Access user ${UserName} |
| VLSI_UNAUTHENTICATED_ACCESS_USER_DELETED | ${UserDisplayName} deleted Unauthenticated Access User ${UserName} |
| VLSI_UNAUTHENTICATED_ACCESS_USER_DELETION_FAILED | ${UserDisplayName} failed to delete Unauthenticated Access User ${UserName} |
| VLSI_UNAUTHENTICATED_ACCESS_USER_UPDATE_FAILED | ${UserDisplayName} failed to update Unauthenticated Access User ${UserName} |
| VLSI_UNAUTHENTICATED_ACCESS_USER_UPDATED | ${UserDisplayName} updated Unauthenticated Access User ${UserName} |
| VLSI_UPDATE_MESSAGE_CLIENT | User ${UserDisplayName} has updated message client ${MessageClientId} in LDAP |
| VLSI_UPDATE_MESSAGE_CLIENT_FAILED | User ${UserDisplayName} failed to update message client ${MessageClientId} in LDAP |
| VLSI_URL_REDIRECTION_CREATE_FAILED | User ${UserDisplayName} failed to create URLRedirection setting ${URLRedirectionDisplayName} |
| VLSI_URL_REDIRECTION_CREATED | User ${UserDisplayName} created URLRedirection setting ${URLRedirectionDisplayName} |
| VLSI_URL_REDIRECTION_DELETE_FAILED | User ${UserDisplayName} failed to delete URLRedirection setting ${URLRedirectionDisplayName} |
| VLSI_URL_REDIRECTION_DELETED | User ${UserDisplayName} deleted URLRedirection setting ${URLRedirectionDisplayName} |
| VLSI_URL_REDIRECTION_UPDATE_FAILED | User ${UserDisplayName} failed to update URLRedirection setting ${URLRedirectionDisplayName} |
| VLSI_URL_REDIRECTION_UPDATED | User ${UserDisplayName} updated URLRedirection setting ${URLRedirectionDisplayName}: (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_URL_REDIRECTION_USER_ENTITLEMENT_ADD_FAILED | ${UserDisplayName} failed to entitle ${EntitlementDisplay} to URLRedirection setting ${URLRedirectionDisplayName} |
| VLSI_URL_REDIRECTION_USER_ENTITLEMENT_ADDED | ${UserDisplayName} entitled ${EntitlementDisplay} to URLRedirection setting ${URLRedirectionDisplayName} |
| VLSI_URL_REDIRECTION_USER_ENTITLEMENT_DELETE_FAILED | ${UserDisplayName} failed to unentitle ${EntitlementDisplay} from URLRedirection setting ${URLRedirectionDisplayName} |
| VLSI_URL_REDIRECTION_USER_ENTITLEMENT_DELETED | ${UserDisplayName} unentitled ${EntitlementDisplay} from URLRedirection setting ${URLRedirectionDisplayName} |
| VLSI_USER_HOME_SITE_ADD_FAILED | ${UserDisplayName} failed to add a user home site with user: ${UserName}, site: ${SiteName}, and optional global entitlement: ${GlobalEntitlementName} |
| VLSI_USER_HOME_SITE_ADDED | ${UserDisplayName} added a user home site with user: ${UserName}, site: ${SiteName}, and optional global entitlement: ${GlobalEntitlementName} |
| VLSI_USER_HOME_SITE_DELETE_FAILED | ${UserDisplayName} failed to delete the user home site with user: ${UserName}, site: ${SiteName}, and optional global entitlement: ${GlobalEntitlementName} |
| VLSI_USER_HOME_SITE_DELETED | ${UserDisplayName} deleted the user home site with user: ${UserName}, site: ${SiteName}, and optional global entitlement: ${GlobalEntitlementName} |
| VLSI_USER_POLICY_DELETE_FAILED | ${UserDisplayName} failed to delete pool ${DesktopId} override policies for user ${UserName} |
| VLSI_USER_POLICY_DELETED | ${UserDisplayName} deleted pool ${DesktopId} override policies for user ${UserName} |
| VLSI_USER_POLICY_UPDATED | ${UserDisplayName} updated pool ${DesktopId} policy for user ${UserName} (${AttrChangeType}: ${AttrName}   ${AttrValue}) |
| VLSI_USERLOGGEDIN | User ${UserDisplayName} has logged in to View Administrator |
| VLSI_USERLOGGEDIN_REST | User ${UserDisplayName} has logged in to Horizon REST API |
| VLSI_USERLOGGEDOUT | User ${UserDisplayName} has logged out of View Administrator |
| VLSI_USERLOGIN_FAIL | User ${UserDisplayName} has failed to authenticate to View Administrator |
| VLSI_USERLOGIN_REST_FAILED | User ${UserDisplayName} has failed to authenticate to Horizon REST API |
| VLSI_USERLOGOFF_REST | User ${UserDisplayName} has logged off from Horizon REST API |
| VLSI_VC_PROVISIONING_DISABLED | ${UserDisplayName} disabled provisioning on vCenter Server ${VCAddress} |
| VLSI_VC_PROVISIONING_DISABLED_FAILED | ${UserDisplayName} failed to disable provisioning on vCenter Server ${VCAddress} |
| VLSI_VC_PROVISIONING_ENABLED | ${UserDisplayName} enabled provisioning on vCenter Server ${VCAddress} |
| VLSI_VC_PROVISIONING_ENABLED_FAILED | ${UserDisplayName} failed to enable provisioning on vCenter Server ${VCAddress} |
| VLSI_VIEW_COMPOSER_OPERATION_CANCEL_FAILED | ${UserDisplayName} failed to cancel ${SVIOperation} for Machine ${MachineName} |
| VLSI_VIEW_COMPOSER_OPERATION_CANCELED | ${UserDisplayName} canceled ${SVIOperation} for Machine ${MachineName} |
| VLSI_VIEW_COMPOSER_OPERATION_HELD | ${UserDisplayName} paused ${SVIOperation} for Machine ${MachineName} |
| VLSI_VIEW_COMPOSER_OPERATION_HOLD_FAILED | ${UserDisplayName} failed to pause ${SVIOperation} for Machine ${MachineName} |
| VLSI_VIEW_COMPOSER_OPERATION_RESUME_FAILED | ${UserDisplayName} failed to resume ${SVIOperation} for Machine ${MachineName} |
| VLSI_VIEW_COMPOSER_OPERATION_RESUMED | ${UserDisplayName} resumed ${SVIOperation} for Machine ${MachineName} |

