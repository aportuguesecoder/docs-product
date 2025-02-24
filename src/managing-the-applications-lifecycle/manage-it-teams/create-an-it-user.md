---
summary: Create IT users for new developers and operators that will operate the platform.
locale: en-us
guid: 67304326-4018-4f4c-88c7-8e5034fe9ce5
app_type: traditional web apps, mobile apps, reactive web apps
---

# Create an IT User

OutSystems allows you to manage IT users like developers, testers, and operators.

When adding a new user they need to be given a username in order to log in to the platform. This username will be their own unique indentifier. Consider that a new developer just joined the company. To create the new IT user, follow these steps:

1. In your LifeTime console (`https://<lifetime_env>/lifetime`), go to the **USER MANAGEMENT** area.

1. Choose **USERS** and click the **New User** link.

1. Fill in the form with the user’s information. You must set the **Default Role** of the user by this time. Afterward, you can grant the user with additional permissions through teams or for specific applications. While selecting the user's **Default Role**, you will get a preview of the default permissions that will be granted to the user by assigning that role.  

    ![](images/user-create-lt.png)

1. Click the **Create** button to create the user.

The user is now created. You can grant the user with **additional permissions** by assigning roles to the user [in teams](about-permission-levels.md#role-assigned-to-users-for-a-team) or [for specific applications](about-permission-levels.md#role-assigned-to-users-for-a-specific-application):

![](images/user-grant-additional-permissions.png)

Check the OutSystems [permission model for IT users](about-permission-levels.md) to better understand which should be the user’s default role and how can you grant the user with additional permissions.

## Centralized user management

LifeTime console (`https://<lifetime_env>/lifetime`) is the master of data for IT users and ensures that every user has the same credentials in all environments that are registered in LifeTime. When you register an environment in LifeTime, from that moment on you will not be able to change the accounts of IT users in the Service Center of that environment.

When you create or update an IT user account in LifeTime, the user's credentials will be updated in LifeTime's database and that change is also propagated to all registered environments. This behavior is also enforced by LifeTime's synchronization process.
