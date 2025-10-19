Project Title: Conversational Recipe Bot for Telegram
This is a "What's for Dinner?" chatbot built in Python, designed to run on the Telegram platform. It helps users find recipes by asking them what ingredients they have on hand.

The bot is built to be highly interactive and user-friendly, guiding the user through a conversation rather than just responding to simple commands.

Core Features
Conversational Interface: Uses the python-telegram-bot library's ConversationHandler to manage a multi-step "stateful" conversation, remembering the user's previous choices.

Interactive Ingredient Selection: Features a "Single Page Checklist" (built with InlineKeyboardMarkup) where users can click to select and deselect multiple ingredients from a grid.

Powerful Recipe Search: Connects to the Spoonacular API, giving it access to thousands of recipes.

Smart Matching: The bot finds recipes that match all the ingredients the user has selected.

Helpful Results: Displays a list of matching recipes, including how many ingredients (if any) the user might be missing for each dish.

Personalized: Includes a "Made by Yasir Siddiqui" signature on all successful results.

Technology Used
Language: Python

Main Library: python-telegram-bot

External API: Spoonacular API

HTTP Requests: requests library

Development Environment: Google Colab
