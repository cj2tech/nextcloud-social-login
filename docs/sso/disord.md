1. Goto [Discord Developmennt page]
(https://discordapp.com/developers/applications/me#top)
2. Click "New Application" button at the top right.

![](/docs/img/discord/1.png)

3. Enter a name for the appliation and check the box to agree to Discord Developer Terms of Service and Policy. Then click create.

![](/docs/img/discord/2.png)

4. On the left click the "0Auth2" tab.

5. Here you will see `ClientID` and `Client Secret` . Click "Reset Secret" button then the "Yes, do it!" button on the pop up. Then note down both.

![](/docs/img/discord/3.png)

6. Click "Add Redirect" Button. Enter in `https://<your.domain.com>/apps/sociallogin/oauth/discord` and click save. *replace "<your.domain.com>" with your URL for Nextcloud.

![](/docs/img/discord/4.png)

7. Goto your Nextcloud Social login settings and enter in noted `ClientID` as the "App id" and the `Client Secret` as the "Secret" and save your changes to complete the setup.