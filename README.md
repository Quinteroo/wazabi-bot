# WAZABI-BOT
![image](https://github.com/user-attachments/assets/45ebb3ad-ba8c-4f90-8482-8e95ac0d286a)



## INTRODUCTION
A Node.js and Gemini AI-powered scaffolding library for WhatsApp bots, designed to automate customer support.

This library empowers developers, entrepreneurs, and businesses to easily create WhatsApp clients, chatbots, applications, and more to meet their business needs.

## LANGUAGE
The source code is developed in TypeScript. However, you can modify it as you wish to work with the language you're most comfortable with.


## PREREQUISITES
* Node.js >= 20
* npm >= 
* ESM
* TypeScript
* API Gemini Google

## DEPENDENCIES
* typescript
* @types/node
* @types/qrcode-terminal
* dotenv
* qrcode-terminal
* whatsapp-web.js

  
## SET UP
Setting up a new project is quite simple with the wazabi-bot CLI. With npm installed, you can create a new wazabi-bot project with the following commands in your OS terminal:

>```bash
>npx wazabi-bot init
>


## GETTING STARTED
1. Use `npx wazabi-bot init` to initialize the project 
2. Install dependencies with `npm install`  
3. Modify content docs in the `/messages` directory  
4. Create a `.env` file in the root of the project  
5. Get your Gemini AI API key from [Google AI Studio](https://aistudio.google.com/app/apikey) and add it to the `.env` file as:
GEMINI_API_KEY=your_api_key_here
6. Build the project using `npm run build`
7. Start the bot `npm start`
8. Scan the QR code with your WhatsApp account
9. Your bot is ready! 🎉

## VIDEO-DEMO
Coming soon

## DISCLAIMER
We build our bot over whatsapp-web.js, which is an unofficial, open-source library that isn't made by WhatsApp or affiliated with it in any way. 
This project is not affiliated, associated, authorized, endorsed by, or in any way officially connected with WhatsApp or any of its subsidiaries or its affiliates. The official WhatsApp website can be found at [whatsapp.com](https://www.whatsapp.com/). "WhatsApp" as well as related names, marks, emblems and images are registered trademarks of their respective owners. Also it is not guaranteed you will not be blocked by using this method. WhatsApp does not allow bots or unofficial clients on their platform, so this shouldn't be considered totally safe. For any businesses looking to integrate with WhatsApp for critical applications, we highly recommend using officially supported methods, such as Twilio's solution or other alternatives. You might also consider the [official API](https://developers.facebook.com/docs/whatsapp/).


## LICENSE
This project is licensed under the Apache License 2.0.
You can find the full license text here:
[LICENSE](https://github.com/Quinteroo/wazabi-bot/blob/main/LICENSE)

### LINKS
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/quinteroo/)
