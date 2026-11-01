# My mod

Mod description goes here...

## Making a sculptr mod

This template is a working sculptr mod: it draws Japanese text with a custom font
([@sculptr/text](https://www.npmjs.com/package/@sculptr/text)), animates a sprite, and
sends messages between the game and the mod. Start from `src/index.ts`.

```sh
npm install
npm run dev        # rebuilds on change and serves http://localhost:8080/index.js
```

While `npm run dev` runs, add `http://localhost:8080/index.js` as a dev mod in your sculptr host and
start a game. Press <kbd>H</kbd> in game to send a ping to the mod and get a pong back.

- `npm run build` writes the finished mod to `dist/index.js`.
- `npm run typecheck` checks the types.
- Set `name`, `displayName` and `description` in `package.json` to your own.
- See [@sculptr/sdk](https://www.npmjs.com/package/@sculptr/sdk) for the mod API.
