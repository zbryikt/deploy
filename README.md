# @zbryikt/deploy

deploy static files to github pages.

## Usage

You will have to ensure the existency of `gh-pages` branch first.

Next, execute this command:

    npx deploy path-to-your-web-root branch


For example, in `@plotdb/sheet` we have `npm run deploy` set to following command:

    npx deploy web/static gh-pages

If omitted, the `branch` parameter will by default be `gh-pages``


## License

MIT
