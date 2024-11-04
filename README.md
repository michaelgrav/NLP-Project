# Fall 2024 CS 6320 Project - 🚲 Bike Repair AI Chatbot

## Project Overview
Our Bike Repair AI Chatbot is designed to assist users with diagnosing and solving common bike issues. Once identifying the issue, the chatbot will then provide steps for the user to fix it. We use natural language processing and machine learning models to allow users to interact with it through simple conversation.

## Features
- **Conversational AI**: The chatbot allows for real-time conversations to troubleshoot bike problems. The AI will remember your problem as the conversation progresses and use what you said throughout the conversation for suggestions.
- **Exit Detection**: The chatbot has been designed to detect when the user's problem is solved and will end the conversation accordingly.
- **Specifically Tailored Knowledgebase**: The chatbot uses a knowledgebase of many bike repair websites and textbooks. These documents have been hand picked for their usefulness and step by step instructions on how to do repairs.
- **Tailoed to the user**: The chatbot will answer to the user based off of their experience with bikes, and will remember their bike specifications when suggesting repairs.
- **Maintenance Tips**: The chatbot will also suggest maintenace tips for the user to prevent future problems.

## Tech Stack
Our chatbot is built entirely within Botpress using many of the built in features such as 
- AI Personality
- AI Tasks to detect user sentiment
- Variables to store user answers such as how experienced they are and their bike specifications
- Guardrails to keep the conversation on topic
- Photos to help users's visualize what the chatbot is talking about

## Sources
Knowledgebase sources
- Parktools: https://www.parktool.com/en-us/blog/repair-help
- Sheldon Brown's blog: https://www.sheldonbrown.com/
- Bike Repair Wiki: https://en.wikibooks.org/wiki/Bicycles/Maintenance_and_Repair
- How to Bike: http://howtobike.info/
- Big Blue Book of Bicycle Repair — 4th Edition: https://www.parktool.com/en-us/product/big-blue-book-of-bicycle-repair-4th-edition-bbb-4

## Project Folder Structure
- The newest release will be placed at the root of the project. Previous releases will be placed in the "Previous Versions" folder.
