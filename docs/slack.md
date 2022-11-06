# Slack Configuration

To configure Slack notifications, you have to create a new app in your namespace and use incoming webhook function. 

* Go to the [Slack API](https://api.slack.com) and choose *Create an app*.

* Pick an option *From scratch*. Choose a name and namespace.

* From your apps page, go to *Incoming webhooks* menu.

![webhook](img/sl_webhook.png)

* Activate incoming webhooks and add a new one to your workspace.

* Now you can use webhook URL in the config.yml for alerts.