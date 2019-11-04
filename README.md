# Cirrus CI 🡒 Discord Webhook
## forked from [DiscordHooks/travis-ci-discord-webhook](https://github.com/DiscordHooks/travis-ci-discord-webhook)


## Requirements
-  You should be using Cirrus CI for testing codes.
-  A Discord Server where notifications will be posted.

## Guide
1.  Create a webhook in your Discord Server ([Guide](https://support.discordapp.com/hc/en-us/articles/228383668-Intro-to-Webhooks)).

1.  Copy the **Webhook URL**.

1.  Go to your repository settings (for which you want status notifications)
    in Travis CI and add an environment variable called `WEBHOOK_URL` and paste
    the **Webhook URL** you got in the previous step.

    ![Add environment variable in Cirrus CI](https://i.imgur.com/UfXIoZn.png)

1.  Add these lines to the `.cirrus.yml` file of your repository.

    ```yaml
    TBD
    ```

1.  Run a build