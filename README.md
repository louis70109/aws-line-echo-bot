# aws-LINE-echo-bot

This is my first project using Serverless framework to create LINE echo bot in AWS.

Release this project to help first time use this framework's developer!

# Bebore you start

1. LINE developer account
2. [LINE Message API](https://developers.line.biz/en/docs/messaging-api/getting-started/)

# Quick Start

1. Install serverless via npm

```bash=
$ npm install -g serverless
```

2. Setup your **AWS** ceritficate

```bash=
export AWS_ACCESS_KEY_ID=<your-key-here>
export AWS_SECRET_ACCESS_KEY=<your-secret-key-here>
```

3. Clone this project

```bash=
$ serverless install --url https://github.com/louis70109/aws-line-echo-bot -n <YOUR_FILE_NAME>
$ cd <YOUR_FILE_NAME>/
```

4. Insert you LINE bot secret & key

```python=
line_bot_api = LineBotApi('YOUR_CHANNEL_ACCESS_TOKEN')
handler = WebhookHandler('YOUR_CHANNEL_SECRET')
```

5. Deploy the webhhok function

```bash=
npm install
pip install -r requirements.txt
serverless deploy
```

Now you can test you chatbot, have fun!
![Echo bot](https://i.imgur.com/Tn1XS13.png)

# Author

Create by NiJia

# Bonus

This project is combined in [serverless example project](https://github.com/serverless/examples/tree/master/aws-python-line-echo-bot)

# License

MIT
