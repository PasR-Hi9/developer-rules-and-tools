#  Hi9 Developer Rules and Tools
## Showcasing our Developer Environment

- [Hi9 Developer Rules and Tools](#hi9-developer-rules-and-tools)
  - [Technologies and Tools](#technologies-and-tools)
  - [GitHub Process](#github-process)
  - [General Coding Guidelines](#general-coding-guidelines)
  - [Formatting](#formatting)
  - [Plugins and Extensions](#plugins-and-extensions)

## Technologies and Tools

 We use the following technologies and tools:
 - JavaScript (ES6), Typescript, Node.js, React 
 - Firebase Cloud Functions (TS, Express.js), Google Cloud Functions (Python, Flask), Firebase Hosting 
 - Google Cloud Scheduler 
 - Databases: Firestore, Big Query, GunDB 
 - SendGrid (emails), MessageBird (WhatsApp, FB Messenger) 
 - Google Maps API, Dialogflow CX API, Google Sheets API 
 - Git, GitHub, GitHub Actions  

## GitHub Process 

 When working together on GitHub, we use the following procedures and processes:
  - Create a new branch for each new feature, and then add a merge request once that feature has been tested.
  - Name branches after the features or issues they address:
       - Use the "Dev" branch for features under development
       - Only merge to the "Master" branch when a new version is released
       - Include an "issue" branch for medium to major bugs
  - Always include meaningful comments for git commits!

## General Coding Guidelines

Our overall system for working on code involves the following:
- Use Visual Studio Code as an editor 
- Use Google Colab when testing Python scripts / sharing with the rest of the team 
- Always specify the exact version of a package 
- Use a requirements.txt to save python dependencies 
- Use 1 tab (worth two spaces) to indent in Python 

## Formatting

To ensure consistency across the team and for ease of reading, our general formatting guidelines are as follows:

- Use lowerCamelCase to name variables and value functions 
- Use UpperCamelCase to name functions 
- Semicolons will not be at the end of commands
    - So commands look like this
    - Not this;

## Plugins and Extensions

On VSC, we use the following plugins and extensions:
- GitLens
- Bracket Pair Colorizer 2
- React Extension Pack (https://marketplace.visualstudio.com/items?itemName=jawandarajbir.react-vscode-extension-pack)

