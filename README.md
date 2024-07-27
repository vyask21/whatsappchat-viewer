# WhatsApp Chat Parser Website

This website allows you to upload a WhatsApp chat log and view its contents.
You can upload a `txt` directly or a `zip` file containing the exported chat.  
In case you export a `zip` file with the option `Attach Media`, you will be able to see images, videos and audio files directly in the website. 

The app runs locally and no logs are sent or stored anywhere.

## How to run locally

1. Clone the git repo
2. Install [Node.js](https://nodejs.org/en/) if you don't have it already
3. Open a terminal in the root of the project and run `npm install` to install the dependencies (optionally with the `--production` flag to avoid installing development dependencies)
4. Run `npm start` to start a development server (while in this mode you can change the code and see the results immediately)
5. Run `npm run build` to build the compiled bundle that you'll find in the `build/` folder

Any local server will do to run the built files.  
It's also possible to download them directly from the [releases page](https://github.com/Pustur/whatsapp-chat-parser-website/releases).

## How to export WhatsApp chats

- [Android](https://faq.whatsapp.com/android/chats/how-to-save-your-chat-history)
- [iPhone](https://faq.whatsapp.com/iphone/chats/how-to-back-up-to-icloud/)


