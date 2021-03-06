# Contributing

The issue tracker can be used to report bugs, make feature suggestions, or browse to see the open issues that are yet to be addressed.

If you wish to contribute to Professor Kauri's development, first open an [issue](https://github.com/Monbrey/professor-kauri-v2/issues) to discuss your idea or perceived bug. If the consensus is that the feature/fix is needed, you can fork the repository and submit a pull request.
Contributing to Kauri will require knowledge of [TypeScript 3.8](https://www.typescriptlang.org/), [discord.js v12](https://discord.js.org/#/docs/main/master/general/welcome), [discord-akairo v8](https://discord-akairo.github.io/) and possibly [Mongoose](https://mongoosejs.com/).

## Setting up your local copy

1. Fork & clone the repository, and make sure you're on the **master** branch
2. Run `npm install` to download and install all additional packages
3. Run `npm install -g typescript` to install the TypeScript compiler globally

## Running and testing your local copy

1. Configure your environment variables as follows:\
NODE_ENV: development\
KAURI_TOKEN: Generated from the [Discord Developer Portal](https://discordapp.com/developers/applications/)\
KAURIDB_URI: Available from Monbrey upon request - may be changed to allow more open development in future
2. Run the TypeScript compiler to build the application: `npm run build`. This will generate the `dist` directory.
3. Run the bot: `node ./dist/index.js`
4. Add your bot to a test server - instructions are available on the [Discord.js Guide](https://discordjs.guide/preparations/adding-your-bot-to-servers.html)

## Developing and submitting changes

1. Commit changes to your own repository
2. Open a [Pull Request](https://github.com/Monbrey/professor-kauri-v2/compare) to merge changes from your repository
3. Include a description of the changes your PR makes and why it should be merged. If your PR addresses an open issue, you can reference it in the description as `Closes #5` or `fixes #12` to automatically link and close issues.
4. Changes will be reviewed and merged as appropriate.
