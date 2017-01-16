# SlackLaTeX
Bot to convert LaTeX code in messages into 

![screen]

##How to use:
Install required modules with:
```
npm install fs
npm install request
npm install websocket
```

Create a secret.txt file in the bot directory and put your slack token in it.

Create a config.txt file that has the username on the first line, and a direct link to the icon you want the bot to have on the second.

Start bot by running `node bot.js` or `nodejs bot.js`.

Any message that starts with '$' and ends with '$' will be turned into an image when bot is on.


[screen]:http://i.imgur.com/7xbkJ6P.png
