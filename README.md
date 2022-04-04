# Yono Bot official translations
Hello, and thank you for taking the time to checkout this Repo. The purpose of this repo is to allow people to contribute to the bot's translations, e.g. new languages, or mistakes. 
## How to contribute to Yono?
You can checkout this [guide](https://gist.github.com/MarcDiethelm/7303312) that will tell you how to fork, and contribute to the translations with the best practicies

## Things to lookout for while translating
```json
    "reasonEmbed": {
        "description": " has been kicked from the server for: "
    }
```
Make sure to keep the spaces in every translation you edit. Removing these could cause your translations to be rejcected from Yono.

```json
     "ban": {
        "description": "Bans the mentioned/given user from the discord server.",
        "usage": [
            {
                 "description": "Bans the user that was mentioned (with reason)",
                "example": "{PREFIX}ban @Moonlightt#2222 5 warning limit exceeded"
            },
            {
                "description": "Bans the user that was mentioned (without reason)",
                "example": "{PREFIX}ban @Moonlightt#2222"
            }
         ]
```
Everything in curly braces, such as {PREIFX} or {USER_RAN_COMMAND} should not be edited, since those are variables.

