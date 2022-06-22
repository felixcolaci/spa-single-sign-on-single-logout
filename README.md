# SSO and Single Logout with Auth0 and two SPAs

This demonstration covers the following use cases:

1. Sign into an application using Auth0 universal login (using authorization code flow)
2. Visit a second application that get's automatically signed in (using auth0 silent authentication)
3. SSO across tabs
4. Single Logout. When both apps run in seperate tabs/windows and either of them get's signed out the other one will notice that and sign the user out as well.

## Auth0 Configuration

Make sure to set the correct values in your auth0 tenant for:

- Allowed Callback URLs
- Allowed Logout URLs
- Allowed Web Origins
- Allowed Origins (CORS)

## App Configuration

Go to each app directory and fill in the correct values into `auth_config.json`.
