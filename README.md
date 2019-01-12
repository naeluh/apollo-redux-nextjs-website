[![Deploy to now](https://deploy.now.sh/static/button.svg)](https://deploy.now.sh/?repo=https://github.com/naeluh/apollo-redux-nextjs-website)

## How to use

Install it and run:

```bash
npm install
npm run dev
# or
yarn
yarn dev
```

Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download)):

```bash
now
```

Note: Do not be alarmed that you see two renders being executed.  Apollo recursively traverses the React render tree looking for Apollo query components. When it has done that, it fetches all these queries and then passes the result to a cache. This cache is then used to render the data on the server side (another React render).
https://www.apollographql.com/docs/react/features/server-side-rendering.html#getDataFromTree
