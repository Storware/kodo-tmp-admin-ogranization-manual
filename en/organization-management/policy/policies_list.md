# Policies list

## List polices

A list will display all policies configured in system

To view the list of polices, select `Policies` from the main menu.

![Main menu Policies section](../../../.gitbook/assets/policymenu.png)

![Policies list view](../../../.gitbook/assets/policy_list.png)

Policies list table view consist of following columns:

| **Field** | **Description** |
| :--- | :--- |
| Policy name | Name of policy |
| Priority | Priority \(see below\) |
| Users count | Numer of users associated with policy |
| Date created | Creation date of policy |
| Created by | Who created policy |
| Date modified | When policy was modified last time |
| Modified by | Who modified policy |
| Action | Quick action menu |

## Default policy

The default server policy has been marked on list **in bold.** Default policy will be used for all new users synced from external source, like e.g. Active Directory.

## Policy priotiy

When user belong to group, group policy will be applied. In case when user belongs to many groups, priority will determine which policy will be applied.

{% hint style="info" %}
The higher priority, the more important the policy is
{% endhint %}

To modify policy priorities, go to the list of policies and then click on `MANAGE PRIORITY`

Grab the selected polic and move \(grab and drop\) it to the selected position. The higher the policy is, the higher priority will be assigned.

![Grab policy and move it around the list](../../../.gitbook/assets/prioryty%20%282%29.png)

