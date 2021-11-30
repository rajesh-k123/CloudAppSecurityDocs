---
title: Manage app policies
ms.date: 11/09/2021
ms.topic: how-to
description: Manage your app governance policies.
---

# Manage app policies

>*[Microsoft 365 licensing guidance for security & compliance](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance).*

To keep up with the latest apps your organization is using, respond to new app-based attacks, and for ongoing changes to your app compliance needs, you might need to manage your app policies in these ways:

- Create new policies targeted at new apps
- Change the status of an existing policy (active, inactive, audit mode)
- Change the conditions of an existing policy
- Change the actions of an existing policy for auto-remediation of alerts

Here's an example of a process for managing an existing policy:

1. Edit the policy:

    - Change the settings of the policy.
    - If needed, change the status to **Audit mode** for testing.

1. Check for expected behavior, such as alerts generated.
1. If the behavior isn't expected, go back to step 1.
1. If the behavior is expected, edit the policy and change its status to active (if needed).

:::image type="content" source="media/app-governance/mapg-manage-policy-process.png" alt-text="The manage app policy workflow." lightbox="media/app-governance/mapg-manage-policy-process.png":::

## Editing an app policy configuration

To change the configuration of an existing app policy:

- Select the policy in the policy list, and then select **Edit** on the app policy pane.
- Select the vertical ellipses for the policy in the list, and then select **Edit**.

For the **Edit policy** page, step through the pages and make the appropriate changes:

- **Description**: Change the description to make it easier to understand the policy's purpose.
- **Severity**
- **Policy settings**: Change the set of apps to which the policy applies. You can also choose to use the existing conditions or modify the conditions
- **Actions**: Change the auto-remediation action for alerts generated by the policy.
- **Status**: Change the policy status.

## Deleting an app policy

To delete an app policy, you can:

- Select the policy in the policy list, and then select **Delete** on the app policy pane.
- Select the vertical ellipses for the policy in the list, and then select **Delete**.

An alternative to deleting an app policy is to change its status to inactive. Once inactive, it won't generate alerts. For example, rather than deleting an app policy for an app with a specific set of conditions that are useful for a future policy, rename the app policy to indicate its usefulness and set its status to inactive. You can later return to the policy and modify it for a similar app and set its status to audit mode or inactive.