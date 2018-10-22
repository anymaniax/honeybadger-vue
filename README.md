# honeybadger-vue

> Honeybadger.io integration for Vue.js

## Project Goals

The goal is to provide an idiomatic, simple integration of HoneyBadger's
exception monitoring service with Vue.js applications.

## Project Status

This version is not yet ready for general use.

## Quick Start

When released, you should be able to consume it with a single `<script>`
tag and a simple init call, as you might do in a minimalist Vue
application. For now, you can simply add it as a dependency to your
project.

```
npm add javascript-vue
```

In your main.js:

```
import HoneybadgerVue from 'honeybadger-vue'

const config = { api_key: (process.env.HONEYBADGER_API_KEY || prompt('Enter the API key for your Honeybadger project:')) }
Vue.use(HoneybadgerVue, config)
```

## Key Assumptions

This project is built using a webpack-based Vue template. It's possible
your own build environment may be just different enough to require some
adjustments. If you find that our artifacts don't quite meet your needs,
please [file an issue on GitHub](https://github.com/honeybadger-io/honeybadger-vue/issues.

## Documentation and Support

For comprehensive documentation and support, [check out our documentation site](http://docs.honeybadger.io/lib/javascript/index.html).

## Changelog

See https://github.com/honeybadger-io/honeybadger-js/blob/master/CHANGELOG.md

## Contributing

1. Fork it.
2. Create a topic branch `git checkout -b my_branch`
3. Commit your changes `git commit -am "Boom"`
3. Push to your branch `git push origin my_branch`
4. Send a [pull request](https://github.com/honeybadger-io/honeybadger-js/pulls)

## Development

<!--TODO: Replace this with something narrowly appropriate for this project -->
``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
HONEYBADGER_API_KEY=yourkey npm run e2e

# run all tests
HONEYBADGER_API_KEY=yourkey npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

### License

The Honeybadger gem is MIT licensed. See the [LICENSE](https://raw.github.com/honeybadger-io/honeybadger-vue/master/LICENSE) file in this repository for details.
