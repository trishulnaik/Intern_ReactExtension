# Browser Extension using React

This project is a browser extension built with React.

## Installation

To install the necessary dependencies, run:

```bash
npm install
# or
yarn
```

## Development

To start the development server, run:

```bash
npm start
# or
yarn start
```

This will open the development server in your default web browser. The page will reload if you make edits and you will see any lint errors in the console.

## Building the Extension

To prepare the extension for deployment, build the project using:

```bash
npm run build
# or
yarn build
```

This command creates a production-ready build of your extension in the `build` directory.

## Loading the Extension in Chrome

1. Open Chrome and go to `chrome://extensions/`.
2. Enable "Developer mode" at the top-right corner.
3. Click on "Load unpacked" and select the `build` folder from your project directory.
4. The extension should now be visible in the list of installed extensions.

## Notes

- Make sure to update the necessary files (`manifest.json`, etc.) in the `public` folder for your extension configuration.
- Test your extension thoroughly before publishing to ensure it behaves as expected in different scenarios.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)