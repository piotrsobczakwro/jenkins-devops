# jenkins-devops with Github

##  "GitHub hook trigger for GITScm polling."


### Prerequisites

On Jenkins install Jenkins Plugin:

**"Manage Jenkins"** -> **"Manage Plugins"** -> **"Available"** tab. Search for **"GitHub plugin"** and install it.

Configure in Jenkins:

Configure GitHub Credentials:
Go to "Manage Jenkins" -> "Manage Credentials" -> "Global" domain -> "Add Credentials".

Choose the kind as "Secret text" and provide your GitHub personal access token.

Configure GitHub Webhook:
In your GitHub repository, go to "Settings" -> "Webhooks" -> "Add webhook".
Set the Payload URL to http://your-jenkins-url/github-webhook/ (replace your-jenkins-url with your Jenkins server URL).
Set the Content type to application/json.
Select "Let me select individual events" and choose "Push" event.
Save the webhook.

Use ngrok to navigate the 



Create Jenkins file







