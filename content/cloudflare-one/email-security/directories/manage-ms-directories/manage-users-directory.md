---
title: Manage users in your directory
pcx_content_type: how-to
weight: 4
---

# Manage users in your directory

Email Security allows you to view and manage the [impersonation registry](/cloudflare-one/email-security/detection-settings/impersonation-registry/) status of your users directory.

On the **MS directory** page, select **Users**.

## Add users to registry

To add a single user to the registry:

1. Select the name you want to add.
2. Select the three dots > **Add to registry**.

To add multiple users to the registry at once:

1. Select the names you want to add to the registry.
2. Select the **Action** dropdown list.
3. Select **Add to registry**.

## Remove users from registry

Email Security allows you to remove users from the registry. 

To remove a single user from the registry:

1. Select the name you want to remove.
2. Select the three dots > **Remove from registry**.

To remove multiple users from the registry at once:

1. Select the names you want to remove from the registry.
2. Select the **Action** dropdown list.
3. Select **Remove from registry**.

## Edit a user

To edit a user in the Microsoft directory:

- Under **Display name**, select the user you want to edit. From here, you can either:
   - Select **Edit**: Enter a **Secondary email**, then select **Save**.
   - Select **Add to registry** to add a user to your registry (this option is displayed if the user is not part of the impersonation registry).
   - Select **Remove from registry** to remove a user from the registry (this option is displayed if the user is part of the impersonation registry).

## Filter a user

You can filter the list of users by registered and unregistered.

A user is registered when they are added to the [impersonation registry](/cloudflare-one/email-security/detection-settings/impersonation-registry/). A user is unregistered when they are not part of the impersonation registry.

To filter the impersonation registry:

Select the **Impersonation registry** dropdown, and choose one of the following:
   - **All**: To view registered and unregistered users.
   - **Registered**: To view registered users.
   - **Unregistered**: To view unregistered users.

To filter users:

Select the **Users** dropdown, and choose one of the following:
   - **All**: To view users in groups and not in groups.
   - **Users in groups**: To view users in groups.
   - **Users not in groups**: To view users not in groups.