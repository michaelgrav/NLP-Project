# Fall 2024 CS 6320 Project - 🚲 Bike Repair AI Chatbot

## Project Overview
Our project is a chatbot that is designed to help users repair their bike. It's designed to help users diagnose and solve common bike issues, across all skill levels. Once identifying the issue, our chatbot will provide steps for the user to fix it. We use natural language processing and machine learning models to allow users to interact with it through simple conversation.

## Project Link
You can test the chatbot here -> https://cdn.botpress.cloud/webchat/v2.1/shareable.html?botId=162d3737-755e-429e-bb18-0479524a68c3

## Features
- **Conversational AI**: The chatbot allows for real-time conversations to troubleshoot bike problems. The AI will remember your problem as the conversation progresses and use what you said throughout the conversation for repair suggestions.
- **Exit Detection**: The chatbot has been designed to detect when the user's problem is solved and will decide to end the conversation accordingly.
- **Specifically Tailored Knowledgebase**: The chatbot uses a knowledgebase of many bike repair websites and textbooks. These documents have been hand picked for their usefulness and step by step instructions on how to do bicycle repairs.
- **Tailoed to the user**: The chatbot will answer to the user based off of their experience with bikes, and will remember their bike specifications when suggesting repairs. For example if the user has hydraulic disc brakes the repair steps will be different than a user who has rim brakes. 
- **Maintenance Tips**: The chatbot will also suggest maintenace tips to the user in order to prevent future bicycle problems.

## Tech Stack
Our chatbot is built entirely within Botpress using many of the built in features such as 
- AI Personality
- AI Tasks to detect user sentiment
- Variables to store user answers such as how experienced they are and their bike specifications
- Guardrails to keep the conversation on topic
- Photos to help users's visualize what the chatbot is talking about

## Sources
Knowledgebase sources - These are some of the sources we use to create the steps for bicycle repairs.
- Parktools: https://www.parktool.com/en-us/blog/repair-help
- Sheldon Brown's blog: https://www.sheldonbrown.com/
- Bike Repair Wiki: https://en.wikibooks.org/wiki/Bicycles/Maintenance_and_Repair
- How to Bike: http://howtobike.info/
- Big Blue Book of Bicycle Repair — 4th Edition: https://www.parktool.com/en-us/product/big-blue-book-of-bicycle-repair-4th-edition-bbb-4

## Project Folder Structure
- The newest release will be placed at the root of the project. Previous releases will be placed in the "Previous Versions" folder.

---
## Diagrams!
### Main flow (happy path)

### Capturing user bike details

### Knowledgebase query

### Ending the conversation
