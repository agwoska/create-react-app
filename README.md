# create-react-app

An easy way to get started with React v18.

This was created since it took so long for me to get started
again after working with React v16.

This app uses my preferences, especially in ESLint.
You can update them if you like.

## Getting Started

Add wanted libraries to _dependencies_ and _devDependencies_ in [package.json](./package.json) and
run `yarn install` to ensure all your libraries are installed for ESLint, debugging, and production.

## Requirements
- Node.js
  - [node](https://nodejs.org/en)
  - [npm](https://www.npmjs.com/)
- [Yarn](https://yarnpkg.com/)

For Debian/Ubuntu installation:
```bash
sudo apt-get update
sudo apt-get install -y nodejs npm
corepack enable
```

## Scripts

### `yarn dev`

Launches development mode in webpack.

Open [http:localhost:3000](http://localhost:3000)
to view it in your preferred browser.

You can change the port in [webpack config](./webpack.config.json).

### `yarn build`

Builds the production build of this app.

### `yarn lint`

Runs ESLint and provides errors and warnings to be fixed.

## Notes

- This app uses [webpack](https://webpack.js.org/). The recommended alternative is
[Vite](https://vitejs.dev/), but I have no experience with it.
- I prefer _yarn_, but you are also able to use _npx_ at your own discretion
- ESLint configuration
  - 0: none
  - 1: warn
  - 2: error

## Disclaimer / Acknowledgement

The [commands](https://github.com/facebook/create-react-app) `npx create-react-app` and `yarn create react-app`
and the React framework are created by the React devs. Creating my React applications would not be possible without them.
