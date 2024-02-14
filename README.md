# Remix Tutorial Walkthrough

Following the [Remix Jokes Tutorial](https://remix.run/docs/en/main/tutorials/jokes)

## Setup

```sh
git clone https://github.com/tohhongxiang123/remix-tutorial-walkthrough.git
cd remix-tutorial-walkthrough

npm install
npx prisma db push
```

## Looking at DB

```sh
npx prisma studio
```

Then go to `http://localhost:5555`


## Development

From your terminal:

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `remix build`

- `build/`
- `public/build/`
