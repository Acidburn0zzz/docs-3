# Users

Create and manage users, user roles and access levels to control how much access users have to your site.

## Users

In the *Users* tab, you can add, activate, block or delete certain users.

A user's profile contains a *Username* (used to login, limited to alphanumeric characters, numbers, dot and underscore), a *Name* (used to display the user across the site) and the *Email*.

The user's profile picture is displayed as a [Gravatar](https://gravatar.com/) depending on the given email address.

![Users overview](images/users.png)

## Permissions

In the *Permissions* tab you can see an overview of user roles and the actions they are allowed to perform.

The permissions are grouped by their according extensions and can be assigned or revoked by toggling the checkboxes. Changes are stored automatically.

**Note** You will have to give the *Access admin area* permission to all roles who should perform any action in the backend, even if it is limited to editing pages. Else they won't be able to reach the pages' admin area.

## Roles

In the *Roles* tab, you can create and manage user roles, a way of organizing users into groups with the same permissions and access levels.

Pagekit comes with a few pre-defined roles, you can also add new ones, if the defaults are not enough for your use-case. The default roles are:

| User / Group     | Description |
|------------------|---------------------------------------------------|
| Anonymous        | Any random visitor to your site.                  |
| Authenticated    | A user with an account who is logged in.          |
| Administrator    | A user with the privilege to perform all actions. |

## Access levels

In the *Access levels* tab, you can configure the visibility of certain parts of your site.

The idea behind this is to set an access level on your content (or menu item etc.) and assign user roles to certain access level. Think of access levels as "Students" and "Teachers" that you've created. That way you can assign content to these groups even when user roles change (new students etc).

By default, you can assign public, registered or special access levels to different parts (menu items, pages etc.) of your website. If the default ones are not enough, you can create and configure your own access levels.
