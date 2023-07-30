# Owner API Authentication

The Tesla Owner API uses a different Access Token than the Local API as well as a different base url.

`Base URL: https://owner-api.teslamotors.com/`

To obtain an Access Token for the Owner API and access your Tesla Account, you can utilize the following apps, which allow you to generate both an Access Token and a Refresh Token from the Tesla server:

- [iOS](https://apps.apple.com/us/app/auth-app-for-tesla/id1552058613#?platform=iphone)
- [Android](https://play.google.com/store/apps/details?id=net.leveugle.teslatokens)

Make sure to copy the Access Token, as it will serve as the Bearer Token for all subsequent Owner API requests, ensuring seamless communication with the API.