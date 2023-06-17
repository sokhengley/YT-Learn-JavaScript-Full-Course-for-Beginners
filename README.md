# Import & Export

- in this session, we need to use `yarn` for package manager and proxy the JavaScript.
- install `yarn` by running below command:

```shell
>sudo npm install yarn
```

- `npm` is the Node Package Manager, if you not yet have it, please install it from the official [website](https://nodejs.org/en/download).

## Quick start:

```
$ yarn # npm install
$ yarn build # npm run build
````

## Development

Run Webpack in watch-mode to continually compile the JavaScript as you work:

```
$ yarn watch # npm run watch
```

- this will auto build once we save our code.
- file `index.html` is the entry point for this package, and it sources the JavaScript file from file `index.pack.js` which is proxy to file `index.js` that we are developing.
- file `index.pack.js` is overwritten everything we build the package.
- please also noted that `watch` mean that it watch our code change and run the build command.