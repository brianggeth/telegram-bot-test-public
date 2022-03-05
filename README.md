# telegram-bot-test-public

This is the base code for a simple telegram Bot.

It uses Now with Vercel for the Deploy

To use it you only need to replace

.post(
            "https://api.telegram.org/bot<your_api_token>/sendMessage"
           
For your own API Token. To get an API Token you can talk to @BotFather the bot manager for Telegram.

To deploy install Now on your sistem with:

npm install -g now

And for deploy run 

Now

If this is your first time using “now”, you will see some instructions for signing in.


Now, all we need to do is let telegram know that our bot has to talk to this url whenever it receives any message. 
We do this through the telegram API. Enter this in your terminal :

curl -F "url=<your-deploy-url>" https://https://api.telegram.org/bot%3Cyour_api_token%3E/setWebhook
  
  
And it's done! Try your bot sending Marco! to him.
