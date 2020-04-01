## React app on netlify

Trying out the deployment process of a react graphql app

## Frontend development workflow

Install and hot deploy all your changes locally, the dev command actually runs gatsby develop on the background
gatsby develop reads up the gatsby-browser and gatsby-config files

```
npm i
npm run dev
```

## Testing the build bundle

gatsby build reads up the gatsby-browser and gatsby-config files


```
gatsby build && gatsby serve
```

more info: https://www.gatsbyjs.org/docs/recipes/deploying-your-site/

## Building

this will read up the netlify.toml configuration

```
netlify deploy
```