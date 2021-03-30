---
title: "Managing user groups"
order: 141
page_id: "managing_user_groups"
warning: false
contextual_links:
  - type: section
    name: "Additional Resources"
  - type: subtitle
    name: "Related Blog Posts"
  - type: link
    name: "Manage Large Teams in Postman with Workspaces, Permissions, and Version Control"
    url: "https://blog.postman.com/postman-team-workspaces-and-permissions/"

---

> __[User groups are only available to Postman Enterprise teams.](https://www.postman.com/pricing)__

With Postman user groups, you can organize your team members into functional groups that mimic your organizational structure. These groups allow you to efficiently manage access control across your team and seamlessly onboard new team members.

You must be a [Postman team admin](/docs/collaborating-in-postman/roles-and-permissions/#team-roles) to create, manage, and delete user groups.

## Contents

* [Creating a user group](#creating-a-user-group)

* [Editing a user group](#editing-a-user-group)

    * [Managing members of a user group](#managing-members-of-a-user-group)

    * [Managing access control for a user group](#managing-access-control-for-a-user-group)

        * [Editing team roles for a user group](#editing-team-roles-for-a-user-group)

        * [Managing roles on workspaces and Postman entities](#managing-roles-on-workspaces-and-postman-entities)

    * [Editing details for a user group](#editing-details-for-a-user-group)

* [Deleting a user group](#deleting-a-user-group)

* [Next steps](#next-steps)

## Creating a user group

As a team admin, you can create a user group by navigating to Postman, selecting **Home** in the upper-left corner, then **Manage Team** on the left side. Above your list of team members, select **Groups** > **Create Group**.

SCREENSHOT CREATE GROUP BUTTON

Give your user group a name and description, add your team members, and select the team roles you would like to assign to the group, then **Create Group**.

SCREENSHOT CREATE GROUP FORM

## Editing a user group

You can edit a user group at any time by managing a group's team members and access to Postman entities.

### Managing members of a user group

In Postman, select **Home** in the upper-left corner, then **Manage Team** on the left side. Above your list of team members, select **Groups**. Locate the group you would like to modify and select it to edit.

Click **+ Add** to add a team member to the user group. Click **X** next to a member to remove them from the user group.

SCREENSHOT ADD OR REMOVE TEAM MEMBERS

### Managing access control for a user group

You can control a user group's access at a team level, workspace level, and on individual collections, APIs, environments, mock servers, and monitors.

#### Editing team roles for a user group

In Postman, select **Home** in the upper-left corner, then **Manage Team** on the left side. Above your list of team members, select **Groups**. Locate the group you would like to modify and select it to edit.

SCREENSHOT EDIT ROLES

Select the team roles you would like to assign to the user group, or deselect team roles you would like to remove from the user group, then **Save Changes**.

#### Managing roles on workspaces and Postman entities

You can control a user group's access to individual workspaces, collections, APIs, environments, mock servers, and monitors. For more information on managing workspaces, see [Sharing workspaces](/docs/collaborating-in-postman/using-workspaces/managing-workspaces/#sharing-workspaces).

For collections, APIs, environments, mock servers, and monitors, navigate to the entity in Postman and in the left sidebar, select **...** > **Manage roles**.

SCREENSHOT MANAGE ROLES ON COLLECTION

Use the search bar to add the user group, then give the group **Editor** or **Viewer** permissions with the dropdown. You can also remove a user group by selecting the **X** to the right of it in the list. Click **Save** to confirm changes.

> See [Defining roles](/docs/collaborating-in-postman/roles-and-permissions/) for more information on access control at a team, workspace, API, and collection level.

### Editing details for a user group

In Postman, select **Home** in the upper-left corner, then **Manage Team** on the left side. Above your list of team members, select **Groups**. Locate the group you would like to modify and select it to edit.

SCREENSHOT EDIT NAME

Click on the user group's name at the top of the page to modify it. To add a description, select **Click To Edit** under the group's name. To update an existing description, select it to modify. **Save Changes** to confirm your updates.

## Deleting a user group

In Postman, select **Home** in the upper-left corner, then **Manage Team** on the left side. Above your list of team members, select **Groups**. Locate the group you would like to delect and select it.

SCREENSHOT DELETE GROUP

**Delete Group** to delete the user group.

## Next steps

Learn more about [defining roles](/docs/collaborating-in-postman/roles-and-permissions/) in your team.