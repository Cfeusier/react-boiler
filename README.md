# React Boiler

> Personal boilerplate for React applications (credit @coryhouse)

### Development Workflow

```shell
# start dev server
npm start -s

# build for deploy
npm run build
```

#### npm Scripts

Note: run all npm scripts with `npm run <command>`, except `start`.

| **Script** | **Description** |
|----------|-------|
| `prestart` | Runs automatically before start. Calls remove-dist script which deletes the dist folder. |
| `start` | Runs tests, lints, starts dev webserver, and opens the app in your default browser. |
| `open` | Opens the app in your default browser. |
| `lint` | Runs ESLint. |
| `lint:watch` | Runs ESLint and watches all files so that they are automatically linted upon save. |
| `clean-dist` | Removes everything from the dist folder. |
| `remove-dist` | Deletes the dist folder |
| `create-dist` | Creates the dist folder and the necessary subfolders. |
| `build:html` | Adds trackJS tracking script and copies to /dist. |
| `build:sass` | Compiles SASS, minifies, generates sourcemap, and stores in /dist. |
| `prebuild` | Runs automatically before build script. Cleans dist folder, builds html, and builds sass. |
| `build` | Bundles all JavaScript using webpack and writes it to /dist. |
| `build:verbose` | Same as above, but verbose. |
| `test` | Runs tests (files ending in .spec.js) using Mocha and outputs results to the command line. Watches all files so tests are re-run upon save. |
| `open-coverage` | View current code coverage via Istanbul. |
