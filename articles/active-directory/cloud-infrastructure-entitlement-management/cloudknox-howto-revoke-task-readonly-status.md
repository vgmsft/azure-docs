---
title: Revoke access to high-risk and unused tasks or assign read-only status for Microsoft Azure and Google Cloud Platform (GCP) identities in the Remediation dashboard in CloudKnox Permissions Management
description: How to revoke access to high-risk and unused tasks or assign read-only status for Microsoft Azure and Google Cloud Platform (GCP) identities in the Remediation dashboard in CloudKnox Permissions Management.
services: active-directory
author: Yvonne-deQ
manager: karenh444
ms.service: active-directory
ms.subservice: ciem
ms.workload: identity
ms.topic: how-to
ms.date: 02/23/2022
ms.author: v-ydequadros
---

# Revoke access to high-risk and unused tasks or assign read-only status for Microsoft Azure and Google Cloud Platform (GCP) identities


> [!IMPORTANT]
> CloudKnox Permissions Management (CloudKnox) is currently in PREVIEW.
> Some information relates to a prerelease product that may be substantially modified before it's released. Microsoft makes no warranties, express or implied, with respect to the information provided here.

This article describes how you can revoke high-risk and unused tasks or assign read-only status for Microsoft Azure and Google Cloud Platform (GCP) identities using the **Remediation** dashboard.

> [!NOTE]
> To view the **Remediation** tab, your must have **Viewer**, **Controller**, or **Administrator** permissions. To make changes on this tab, you must have **Controller** or **Administrator** permissions. If you don’t have these permissions, contact your system administrator.

## View an identity's permissions

1. On the CloudKnox home page, select the **Remediation** tab, and then select the **Permissions** subtab.
1. From the **Select an authorization system type** dropdown, select **Azure** or **GCP**.
1. From the **Select an authorization system** dropdown, select the accounts you want to access.
1. From the **Search for** dropdown, select **Group**, **User**, or **APP**.
1. To search for more parameters, you can make a selection from the **User States**, **Privilege Creep Index**, and **Task usage** dropdowns.
1. Select **Apply**.

    CloudKnox displays a list of groups, users, and service accounts that match your criteria.
1. In **Enter a username**, enter or select a user.
1. In **Enter a group name**, enter or select a group, then select **Apply**.
1. Make a selection from the results list.

    The table displays the **Username** **Domain/Account**, **Source**, **Resource** and **Current role**.


## Revoke an identity's access to unused tasks

1. On the CloudKnox home page, select the **Remediation** tab, and then select the **Permissions** subtab.
1. From the **Select an authorization system type** dropdown, select **Azure** or **GCP**.
1. From the **Select an authorization system** dropdown, select the accounts you want to access.
1. From the **Search for** dropdown, select **Group**, **User**, or **APP**, and then select **Apply**.
1. Make a selection from the results list.

1. To revoke an identity's access to tasks they aren't using, select **Revoke unused tasks**.
1. When the following message displays: **Are you sure you want to change permissions?**, select: 
    - **Generate Script** to generate a script where you can manually add/remove the permissions you selected.
    - **Execute** to change the permission.
    - **Close** to cancel the action.

## Revoke an identity's access to high-risk tasks

1. On the CloudKnox home page, select the **Remediation** tab, and then select the **Permissions** subtab.
1. From the **Select an authorization system type** dropdown, select **Azure** or **GCP**.
1. From the **Select an authorization system** dropdown, select the accounts you want to access.
1. From the **Search for** dropdown, select **Group**, **User**, or **APP**, and then select **Apply**.
1. Make a selection from the results list.

1. To revoke an identity's access to high-risk tasks, select **Revoke high-risk tasks**.
1. When the following message displays: **Are you sure you want to change permissions?**, select: 
    - **Generate Script** to generate a script where you can manually add/remove the permissions you selected.
    - **Execute** to change the permission.
    - **Close** to cancel the action.

## Revoke an identity's ability to delete tasks

1. On the CloudKnox home page, select the **Remediation** tab, and then select the **Permissions** subtab.
1. From the **Select an authorization system type** dropdown, select **Azure** or **GCP**.
1. From the **Select an authorization system** dropdown, select the accounts you want to access.
1. From the **Search for** dropdown, select **Group**, **User**, or **APP**, and then select **Apply**.
1. Make a selection from the results list.

1. To revoke an identity's ability to delete tasks, select **Revoke delete tasks**.
1. When the following message displays: **Are you sure you want to change permissions?**, select: 
    - **Generate Script** to generate a script where you can manually add/remove the permissions you selected.
    - **Execute** to change the permission.
    - **Close** to cancel the action.

## Assign read-only status to an identity

1. On the CloudKnox home page, select the **Remediation** tab, and then select the **Permissions** subtab.
1. From the **Select an authorization system type** dropdown, select **Azure** or **GCP**.
1. From the **Select an authorization system** dropdown, select the accounts you want to access.
1. From the **Search for** dropdown, select **Group**, **User**, or **APP**, and then select **Apply**.
1. Make a selection from the results list.

1. To assign read-only status to an identity, select **Assign read-only status**.
1. When the following message displays: **Are you sure you want to change permissions?**, select: 
    - **Generate Script** to generate a script where you can manually add/remove the permissions you selected.
    - **Execute** to change the permission.
    - **Close** to cancel the action.
    

## Next steps

- For information on how to view existing roles/policies, requests, and permissions, see [View roles/policies, requests, and permission in the Remediation dashboard](cloudknox-ui-remediation.md).
- For information on how to create a role/policy, see [Create a role/policy](cloudknox-howto-create-role-policy.md).
- For information on how to clone a role/policy, see [Clone a role/policy](cloudknox-howto-clone-role-policy.md).
- For information on how to delete a role/policy, see [Delete a role/policy](cloudknox-howto-delete-role-policy.md).
- For information on how to modify a role/policy, see Modify a role/policy](cloudknox-howto-modify-role-policy.md).
- To view information about roles/policies, see [View information about roles/policies](cloudknox-howto-view-role-policy.md).
- For information on how to attach and detach permissions for AWS identities, see [Attach and detach policies for AWS identities](cloudknox-howto-attach-detach-permissions.md).
- For information on how to add and remove roles and tasks for Azure and GCP identities, see [Add and remove roles and tasks for Azure and GCP identities](cloudknox-howto-attach-detach-permissions.md).
- For information on how to create or approve a request for permissions, see [Create or approve a request for permissions](cloudknox-howto-create-approve-privilege-request.md).