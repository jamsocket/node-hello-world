# node-hello-world

This is a simple NodeJS Hello World server built using Express.

### Run as a session backend on Jamsocket:

```sh
npx jamsocket login
```

```sh
npx jamsocket service create hello-world
```

```sh
npx jamsocket push hello-world -f ./Dockerfile --include-git-commit
```

```sh
npx jamsocket connect hello-world
```

### Run locally:

```sh
npm install
npm start
```
