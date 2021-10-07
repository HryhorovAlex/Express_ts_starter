# Express Starter

## `Starter` includes next:

1. Express
2. Typescript
3. Prettier
4. eslint with `airbnb-base` extension
5. basic scripts: `start`, `dev` `build`

## `Scripts`

1. `start` - runs root file inside `dist` folder, index.js, which creates in case of the build.

2. `dev` - runs `index.ts` file inside `src` folder with `nodemon` for support live update.

3. `build` - compiles `ts` to `js` and puts it into the newly created `dist` folder.

## `How to start`

1. Make sure that the latest stable `node` version is installed and chosen on your machine.

2. Clone the repo.

3. Enter to the folder and install node modules:

```
cd express_ts_starter && npm i
```

4. Create `.env` with PORT=`5000`.

5. Use scripts to start the app.
