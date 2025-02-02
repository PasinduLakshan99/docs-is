# Invite user to set password

Allow administrator to invite users to set their own passwords during the onboarding process in {{product_name}}.

## Configuration instructions

For inviting users to set their password, follow these instructions:

1. On the {{product_name}} Console, go to **User Onboarding** > **Invite User to Set Password**.
2. Check the **Enable user email verification** if a verification step is required during user creation.
3. Select the **Enable account lock on creation** to lock the user account during creation.
4. If you want to send an account activation email, make sure the corresponding option is enabled.
5. Set the **Email verification code expiry time** and **Ask password code expiry time** to define how long the codes should be valid.
6. Click **Update** to save the changes.

![Invite User to Set Password Configuration]({{base_path}}/assets/img/guides/account-configurations/invite-user-to-set-password.png)

## Parameters

<table>
  <tr>
    <th>Parameter</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Enable user email verification</td>
    <td>Triggers a verification notification during user creation if enabled.</td>
  </tr>
  <tr>
    <td>Enable account lock on creation</td>
    <td>Locks the user account during creation to prevent unauthorized access.</td>
  </tr>
  <tr>
    <td>Send account activation email</td>
    <td>Sends an email to users for account activation if enabled.</td>
  </tr>
  <tr>
    <td>Email verification code expiry time</td>
    <td>The duration in minutes for which the email verification code remains valid.</td>
  </tr>
  <tr>
    <td>Password Setup Invitation Code Expiration Time</td>
    <td>Defines the validity period in minutes for the password setup code sent to users. For infinite validity period, set -1.</td>
  </tr>
</table>
