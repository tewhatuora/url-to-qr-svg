# URL to QR Code (SVG)

Generate a QR Code (in SVG format) from a URL

This repo produces an HTML file, that when loaded within GitHub pages will prompt the user for a string (URL), and then using their browser, generate an SVG QR code based on the given string.

## Development

### Notes

This repo has its `node_modules` folder committed to source control, to help monitor any changes in the dependencies.
As such, try to keep this repo as light on dependencies as possible.

### Dependencies

- Node.js `v16.10.0`
- `http-server` (global NPM dependency)

### Set up dev environment

#### Set up dependencies

If you're using NVM or asdf, make sure you're using the desired version of Node, as mentioned above.

```bash
node -v
```

If you haven't installed `http-server` globally, please do that now:

```bash
npm i -g http-server
```

#### Running the dev server

```bash
npm start
```

### Publishing

Once your changes are in the `main` branch, GitHub Pages will deploy everything in this repo to [https://tewhatuora.github.io/url-to-qr-svg/](https://tewhatuora.github.io/url-to-qr-svg/)