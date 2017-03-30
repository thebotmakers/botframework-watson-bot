# botframework-watson-bot

> An Custom Bot to use IBM's Watson Conversation service with Misocroft's Bot Framework

[![NPM Version][npm-image]][npm-url]

## Install

```bash
npm i -S botframework-watson-bot
```

## Usage

First, create your Intents, Entities and Dialogs in Watson's UI.

Then, create a bot instance like you would with `UniversalBot`, but only Watson's service credentials and Workspace Id are needed:

```ts
let bot = new WatsonBot(connector, { password: '<your-password>', username: 'your-<username>', workspace: '<workspace-id>' });
```

## Implemented

- text messages between Conversation service and the bot

## Missing

- quick replies
- attachments
- custom actions using `bot.beginDialogAction` (alows you to react to facebook's get started button)

## Todo

- Unit tests

## Check us out!

https://www.thebotmakers.com

## License

[MIT](http://vjpr.mit-license.org)

[npm-image]: https://img.shields.io/npm/v/botframework-watson-bot.svg
[npm-url]: https://npmjs.org/package/botframework-watson-bot