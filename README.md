# svelte app
Folked from [sveltejs/template](https://github.com/sveltejs/template) and be customized.

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit leechiryo/template svelte-app
cd svelte-app
```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*


## Get started

Install the dependencies...

```bash
cd svelte-app
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Different with the origin template, the http server will not be started.

The compiled js and css file will be output to the directory ./public/build/

## Building and running in production mode

To create an optimised version of the app:

```bash
npm run build
```

You can run the newly built app with `npm run start`. This uses [sirv](https://github.com/lukeed/sirv), which is included in your package.json's `dependencies` so that the app will work when you deploy to platforms like [Heroku](https://heroku.com).

