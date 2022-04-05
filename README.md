# Yono Bot official translations
Hello, and thank you for taking the time to checkout this Repo. The purpose of this repo is to allow people to contribute to the Yono's translations, e.g. new languages, or fix mistakes in current translations. 
## How to contribute to Yono?
You can checkout this [guide](https://gist.github.com/MarcDiethelm/7303312) that will tell you how to fork, and contribute to the translations with the best practicies

## Things to lookout for while translating
```json
{
    "reasonEmbed": {
        "description": " has been kicked from the server for: "
    }
}
```
##Make sure to keep the spaces in every translation you edit. Removing these could cause your translations to be rejected from being used by Yono.

```json
{
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
    }
}
```
## Any text you see that is in between curly braces `{}` should not be translated as these are variables used to insert information into the strings at the time it is needed. 
```json
"fields": [
    {
        "name": "{EMOJI_MEMBERS} Joins",
        "value": "",
        "inline": true
    },
    {
        "name": "{EMOJI_SRVLEAVES} Leaves",
        "value": "",
        "inline": true
    },
    {
        "name": "{EMOJI_PLUS} Bonus",
        "value": "",
        "inline": true
    }
]
```
## Make sure to not to edit boolean values `true` or `false`. Any text that is empty example: `""` should be left alone.

```json
{
    "responses": [
        "It is certain.",
        "It is decidedly so.",
        "Without a doubt.",
        "Yes definitely.",
        "As I see it, yes.",
        "Most likely.",
        "Outlook good.",
        "Yes.",
        "Signs point to yes.",
        "Reply hazy try again.",
        "Ask again later.",
        "Better not tell you now.",
        "Cannot predict now.",
        "Concentrate and ask again.",
        "Don't count on it.",
        "My reply is no.",
        "Outlook not so good.",
        "Very doubtful.",
        "No way.",
        "Maybe",
        "No.",
        "||No||",
        "||Yes||",
        "Hang on",
        "It's over",
        "It's just the beginning"
    ]
}
```
`||No||`, and `||Yes||`. Please put your response inbetween of `||`, example: `||Translation Here||`
