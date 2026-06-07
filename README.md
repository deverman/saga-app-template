# saga-app-template

Template repository for creating App landing pages using the [Saga](https://getsaga.dev) static site generator.

## Requirements

- Swift 6.0+
- macOS 14+
- Saga CLI

## Install the Saga CLI

```bash
brew install loopwerk/tap/saga
```

## Development

Start a local dev server that watches for changes and auto-reloads the browser:

```bash
saga dev
```

The site will be available at `http://localhost:3000`. Saga watches both the `content/` folder and `Sources/` for changes — content edits trigger an in-process rebuild, while Swift source changes trigger a recompile.

To use a different port:

```bash
saga dev --port 8080
```

## Production Build

```bash
saga build
```

Output is written to the `deploy/` folder.
