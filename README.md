# fatbot-htn-demo
This is the demo repository for the Facebook Messenger Bot built during Hack the North 2016. It was a joint effort by Shamil Khan, Hammad Mirza and Sarim Zafar

## Idea behind the Bot

The main purpose of the bot was to replace the manual effort that every person has to go through when recording their daily food intake. Instead of calculating how much calories an apple has and then manually storing that information in a diet-tracking app (ex. MyFitnessPal) the Bot automates this process for you.

# Example 

Input from the user : 'I ate 2 apples for snack'
Output from the Bot : 'That was 190 calories. 2110 calories to go for the day'

The bot also has the capability to show various graphs relating to regular calorie intake, daily goals and eating frequency.

# Technical 

The bot is built using a JavaScript front-end library called BootBot. The library helps modularize conversations and is reponsible for fetching and posting information. The bot also utilizes Google's Natural Language Processing API for parsing the user input and converting into meaningful data. 

For the calorie database, the project uses FatSecret API which is communicated mostly through the bot's PHP backend. Most of the graph generation and data processing occurs on its PHP framework. 

There were 2 main use cases for the bot :

## Use Case 1 - Configuration

https://www.youtube.com/watch?v=2JWZKoGakzU

## Use Case 2 - User Conversations

https://www.youtube.com/watch?v=0fjwo_5ToLs
