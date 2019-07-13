# awesome-sanity [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources related to [Sanity.io](https://sanity.io/), the Platform for Structured Content.

## Contents

- [Official Resources](#official-resources)
- [Plugins](#plugins)
- [Integrations](#integrations)
- [Sample Projects](#sample-projects)
    - [Sanity.io/create templates](#sanity.io%2Fcreate-templates)
    - [Other examples](#other-examples)
    - [How to's](#how-to's)
    - [Studio inspiration](#studio-inspiration)
- [Related Projects](#related-projects)
- [Media](#media)
    - [Articles and blogs](#articles-and-blogs)
    - [Podcasts](#podcasts)
    - [Videos](#videos)


## Official Resources

Official resources posted by the Sanity.io team.

- [Sanity.io](http://sanity.io/) - Project website
- [Docs](https://www.sanity.io/docs/) - Official documentation
- [Sanity.io/create](https://www.sanity.io/create) - Have a Sanity powered site up and running in minutes
- [Roadmap](https://www.sanity.io/docs/misc/roadmap) - The project roadmap.
- [Sanity.io Blog](https://www.sanity.io/blog) - Great articles written by the Sanity.io team
- [Status page](https://status.sanity.io/) - Check if all systems are operational
- [`sanity-recipes`](https://github.com/sanity-io/sanity-recipes) - Collection of recipies / snippets / frequently asked questions about Sanity.
- [Slack community](https://slack.sanity.io/) - Essential Slack community with more than a thousand Sanity.io users. The core team hangs out there too!  

## Plugins

Sanity is built in React.js and plugins allow you to create and include components that compose or override existing functionality.  
Use `sanity install {plugin-name}` to install a plugin.

- [`@sanity/code-input`](https://github.com/sanity-io/sanity/tree/next/packages/%40sanity/code-input) - Adds a new `type: 'code'` field type.
- [`@sanity/color-input`](https://github.com/sanity-io/sanity/tree/next/packages/%40sanity/color-input) - Adds a new `type: 'color'` field type. 
- [`@sanity/dashboard`](https://github.com/sanity-io/sanity/tree/next/packages/%40sanity/dashboard) - Add the [dashboard tool](https://www.sanity.io/docs/content-studio/dashboard) to your studio.
- [`@sanity/google-maps-input`](https://github.com/sanity-io/sanity/tree/next/packages/%40sanity/google-maps-input) - Provides a more visual way to input the coordinates of a geopoint field.
- [`@sanity/production-preview`](https://github.com/sanity-io/sanity/tree/next/packages/%40sanity/production-preview) - Add a link from the content studio to a preview path on your site. ([Read more](https://www.sanity.io/docs/content-studio/preview-content-on-site))
- [`@sanity/rich-date-input`](https://github.com/sanity-io/sanity/tree/next/packages/%40sanity/rich-date-input) - A richer date/time type and input component for Sanity form builder
- [`@sanity/vision`](https://github.com/sanity-io/sanity/tree/master/packages/@sanity/vision) - A tool that allows you to quickly query data from your studio. ([Read more](https://www.sanity.io/docs/front-ends/the-vision-plugin))
- [`dark-theme`](https://github.com/sanity-io/dark-theme) - Dark theme for the sanity studio
- [`sanity-plugin-datatable`](https://www.npmjs.com/package/sanity-plugin-datatable) - Adds a new `type: 'table'` field type.
- [`sanity-plugin-highcharts-editor`](https://github.com/nilsnh/sanity-plugin-highcharts-editor) - This plugin let's you embed the Highcharts Editor within Sanity.
- [`sanity-plugin-intercom`](https://www.npmjs.com/package/sanity-plugin-intercom) - This plugin adds a new tool in your Sanity Content Studio with the Intercom-widget.
- [`sanity-plugin-json-input`](https://www.npmjs.com/package/sanity-plugin-json-input) - Adds a new `type: 'json'` field.
- [`sanity-plugin-latex-input`](https://github.com/sanity-io/latex-input) - Enables LaTeX math forumla input with preview capabilities
- [`sanity-plugin-markdown`](https://github.com/rexxars/sanity-plugin-markdown) - Adds a new `type: 'markdown'` field type. 
- [`sanity-plugin-mux-input`](https://github.com/sanity-io/sanity-plugin-mux-input) - Adds a new `type: 'mux.video'` field type.
- [`sanity-plugin-nyancat-spinner`](https://github.com/rexxars/sanity-plugin-nyancat-spinner) - Replace default spinners with NYANCAT SPINNERS OMG
- [`sanity-plugin-podcast`](https://www.npmjs.com/package/sanity-plugin-podcast) - Podcast plugin for Sanity that creates schemas for podcasts and episodes with necessary iTunes data.
- [`sanity-plugin-sanity-datatable`](https://www.npmjs.com/package/sanity-plugin-sanity-datatable) - Adds a new `type: 'table'` field type.
- [`sanity-plugin-table`](https://github.com/rdunk/sanity-plugin-table) - Adds a new `type: 'table'` field type.
- [`sanity-plugin-timelinejs`](https://github.com/kmelve/sanity-plugin-timelinejs) - This plugin installs schemas for hosting content for Timeline.js. ([Example](https://codesandbox.io/s/5w2xv3moox))
- [`sanity-plugin-url-metadata-input`](https://github.com/sanity-io/sanity-plugin-url-metadata-input) - URL input for Sanity that retrieves metadata (title, description) along with OpenGraph information
- [`sanity-plugin-webamp`](https://www.npmjs.com/package/sanity-plugin-webamp) - This plugin adds [Webamp](https://webamp.org/) as a tool in your Sanity Studio.
- [`unicorn-slider`](https://github.com/sanity-io/unicorn-slider) - Sample input plugin implemented in the [Custom input widget guide](https://www.sanity.io/docs/extending/custom-input-widgets)

The following plugins are not yet production ready, use at your own risk:
- [`sanity-plugin-draft-review`](https://github.com/gustavorino/sanity-plugin-draft-review) - Sanity draft review plugin
- [`sanity-plugin-search-groq-filter`](https://github.com/sanity-io/sanity-plugin-search-groq-filter) - Adds support for GROQ filters in search queries in Sanity

### Plugins as source code
These plugins are not directly installable using `sanity install` but you can check the source code and include them as local plugins

- [`barcode-input`](https://github.com/sanity-io/sanity/tree/next/packages/ecommerce-studio/plugins/barcode-input) - Originally part of the [ecommerce-studio](https://github.com/sanity-io/sanity/tree/next/packages/ecommerce-studio) this input field allows you to enter a barcode you can scan

### Plugin templates

- [`plugin-template-chess-input`](https://github.com/sanity-io/plugin-template-chess-input) - Plugin template for input component modelling a chess board, including preview
- [`plugin-template-logo`](https://github.com/sanity-io/plugin-template-logo) - Plugin template for a studio logo
- [`plugin-template-tool-with-routing`](https://github.com/sanity-io/plugin-template-tool-with-routing) - Plugin template for a tool that includes basic routing.

### Dashboard plugins
These plugins add widgets or functionality to your dashboard tool.
- [`minesweeper`](https://github.com/tkalve/minesweeper) - Dashboard widget for the Sanity Content Studio which gives you a minesweeper game.
- [`sanity-plugin-dashboard-widget-document-chart`](https://github.com/thomax/sanity-dashboard-widget-document-chart) - Sanity dashboard widget which graphs out count of doctypes
- [`sanity-plugin-dashboard-widget-gatsby`](https://github.com/gatsby-inc/sanity-plugin-dashboard-widget-gatsby) - A dashboard widget plugin for Gatsby Preview and Sanity
- [`sanity-plugin-dashboard-widget-notes`](https://github.com/mrkolby/sanity-plugin-dashboard-widget-notes) - Dashboard widget for the Sanity Content Studio which lets you write simple "post-it" notes
- [`sanity-plugin-dashboard-widget-netlify`](https://github.com/sanity-io/sanity-plugin-dashboard-widget-netlify) - Sanity Studio Dashboard Widget for triggering Netlify builds

## Integrations

- [`gatsby-source-sanity`](https://github.com/sanity-io/gatsby-source-sanity) - Easy way to pull data from Sanity into Gatsby websites.
- [Sane Shopify](https://github.com/good-idea/sane-shopify) - Integration between Sanity and the Shopify Storefront API.
- [MDX-deck with Sanity](https://github.com/kmelve/sanity-with-mdx-deck) - Generate an [mdx-deck](https://github.com/jxnblk/mdx-deck) from Sanity.io
- [`contentful-to-sanity`](https://www.npmjs.com/package/contentful-to-sanity) - This package liberates Contentful spaces, creating Sanity projects and schemas as it goes.

## Sample projects

### Sanity.io/create templates
- [Gatsby blog powered by Sanity](https://github.com/sanity-io/sanity-template-gatsby-blog)
- [Gatsby portfolio site powered by Sanity](https://github.com/sanity-io/sanity-template-gatsby-portfolio)
- [Landing page builder in Next.js](https://github.com/sanity-io/sanity-template-nextjs-landing-pages)
- [Conference site in Vue / Nuxt](https://github.com/sanity-io/sanity-template-nuxt-events)
- [Blog template with a Svelte front-end](https://github.com/sanity-io/sanity-template-sapper-blog)

### Other examples
- [The Transglobal Candy Store](https://github.com/sanity-io/example-ecommerce-snipcart-vue) - Sample front-end for the Sanity.io e-commerce schema with vue.js, nuxt.js, and snipcart
- [Microservice for transcribing audio files](https://github.com/sanity-io/sanity-microservice-transcription) - Microservice for transcribing audio files uploaded to sanity.io
- [Cats dashboard widget](https://github.com/sanity-io/example-dashboard-widget-cats) - A dashboard widget for Sanity Content Studio

### How-to's
- [Netlify from Sanity](https://github.com/sanity-io/netlify-form-sanity) - How to use Netlify Forms and Functions to submit data to Sanity.io

### Studio Inspiration
Other people's approach to structuring the studio
- [Movie CMS](https://github.com/mornir/movie-cms) - Movie CMS using Sanity.io
- [Hikawa.studio CMS](https://github.com/good-idea/hikawa.studio) - React+SSR for hikawa.studio via Sanity.io + Shopify GraphQL API 
- [Rendah Mag CMS](https://github.com/danjonesdev/rendah-mag-sanity-cli) - Sanity.io dashboard for Rendah Mag
- [byteconf-sanity-schema](https://github.com/byteconf/byteconf-sanity-schema) - The sanity.io schema for byteconf.com
- [perezperret.com CMS](https://github.com/perezperret/perezperret.com-cms) - sanity.io headless CMS for perezperret.com
- [SeedTribe CMS](https://github.com/harrycresswell/seedtribe-api) - An API for SeedTribe content built using Sanity.io
- [Itinerary studio](https://github.com/thomax/itinerary-studio) - Studio for planning a journey

## Related projects

- [Official: GROQ](https://sanity-io.github.io/GROQ/) - **G**raph-**R**elational **O**bject **Q**ueries, the query language and execution engine for filtering and projecting JSON documents.
- [Official: Portable Text](https://portabletext.org/) - Portable Text is a JSON based rich text specification for modern content editing platforms.
- [Official: `vscode-sanity`](https://github.com/sanity-io/vscode-sanity) - Visual Studio Code extension for developing applications powered by Sanity.io
- [Sanity Query Helper](https://github.com/staccx/sanity-query-helper) - Helper for using Sanity.io and generating GROQ
- [`dumbo-ears`](https://github.com/rexxars/dumbo-ears) - Small(ish) listener implementation for Sanity. Useful if you only need listeners.
- [`picosanity`](https://github.com/rexxars/picosanity) - Tiny Sanity client alternative, if you only need to do queries and only need to support modern browsers.
- [`podcast-to-sanity`](https://github.com/sanity-io/podcast-to-sanity) - This CLI lets you import podcasts into Sanity via their RSS-feed.
- [`react-sanity-pagination`](https://github.com/dane-brown/react-sanity-pagination) - React pagination for Sanity.io
- [`reflector-client`](https://www.npmjs.com/package/reflector-client) - Implements the messaging protocol that supports the Sanity real time presence exprience.

## Media

### Articles and blogs
- [Make a Serverless Slack Notification Service – “A post was updated in Sanity”](https://dev.to/sanity-io/someone-created-a-post-in-sanity-make-a-serverless-slack-notification-service-373i) - Knut Melvær 
- [Make your own podcasting platform!](https://dev.to/kmelve/make-your-own-podcasting-platform-e5o) - Knut Melvær 
- [My brand new blog powered by Sanity.io](https://staticfirst.dev/blog/2019/04/my-brand-new-blog-powered-by-sanity-io-gatsby/) - Markus Schork
- [Norwegian CMS startup Sanity - The New Kid in Town](https://www.cms-connected.com/News-Archive/June-2018/Norwegian-CMS-startup-Sanity-The-New-Kid-in-Town) - CMS Connected

### Podcasts
- [Structured Content Done Right with San​i​ty​.io](https://devmode.fm/episodes/structured-content-done-right-with-sanity-io) - devMode.fm
- [Headless CMS - Interview with Simen Svale Skogsrud](https://cherryleaf.podbean.com/e/48-headless-cms-interview-with-simen-svale-skogsrud/) - The Cherryleaf Podcast
- [Syntax.fm](https://syntax.fm/) - Sanity is a regular sponsor of Syntax.fm

### Videos
- [Official Youtube Channel](https://www.youtube.com/channel/UCGz69JwGRptteFAaX8hSKCQ)
- [Sanity | ReactJS Norway](https://www.youtube.com/watch?v=oIECLhOpAns) - One of the very first public presentations about Sanity
- [Build a Portfolio Site with Sanity.io and Gatsby - Learn with Jason](https://github.com/jlengstorf/sanity-gatsby-portfolio) - [Espen Hovlandsdal](https://twitter.com/rexxars) teaches [Jason Lengstorf](https://twitter.com/jlengstorf) how to build a portfolio site using Sanity.io and Gatsby. (Repos: [Site](https://github.com/jlengstorf/sanity-gatsby-portfolio), [Studio](https://github.com/jlengstorf/sanity-portfolio-studio))

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Passionate People has waived all copyright and
related or neighboring rights to this work.

[//]: # (Original author: Israel Roldan)
