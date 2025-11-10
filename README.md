# Mini intergrator app - Slack webhook

 utilizing the slack webhooks this app allow users to perform various task like retrieving messages, posting messages and so on

## installantion
fork the repo

```bash
 # if you are using https clone 
git clone https://github.com/your-github-username/mini-intergrator-slack-webhook.git
```
for ssh
```bash
 git clone git@github.com:your-github-username/mini-intergrator-slack-webhook.git
```
> [!NOTE]
> In both the above cases make sure to replace `your-github-username` with your own username for it to work

<p> To run a local instance clone it to your local machine</p>

```bash
 #the cd it the project folder
 cd mini-intergrator-slack-webhook
```

install the depenancies

```bash
npm install 
```

Remember to add your slack environmental variables to a `.env` file
in this format 
```bash 
 PORT=Your_prefered_Port
SLACK_WEBHOOK_URL=Your_Slack_Webhook_Url
USE_SLACK_BLOCKS=false
```
from here you can start you development instance like so 

```bash 
 npm run dev
 ```

 ### Features
 - post a message to a predefined channel
 - read the messages in slack
 - query posted messages 

### In the pipeline
 - delete messages based on  a given timeline
 - formart the message layout