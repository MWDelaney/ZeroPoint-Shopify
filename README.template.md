# πͺzero_point_shopify

A free, new-user-friendly website starter project designed to walk you through creating, editing, and publishing any web project; from a personal blog, to a company website!

Read more at [https://getZero-Point-Shopify.com](https://getZero-Point-Shopify.com)!

## What is zero_point_shopify?

### For new users

_zero_point_shopify_ is a free, new-user-friendly website starter designed to walk you through creating and publishing a fast, secure web project using modern tools and technology. zero_point_shopify makes it easy to "get up to zero" and start building your site.

### For experienced developers

_zero_point_shopify_ is a modern, opinionated, bare-bones Jamstack starter using Eleventy to get "up to zero" on a project quickly and easily.
Why you might choose _zero_point_shopify_ as your Jamstack starter:

* Powered by Eleventy, which [rocks](https://11ty.rocks)!
* No CSS frameworks or libraries; use whatever you like best
* GitHub Action replaces the zero_point_shopify name throughout the site with your project's name!
* Custom generated project-specific [readme file](https://github.com/MWDelaney/zero_point_shopify/blob/master/README.zero_point_shopify.md) to help you take the next steps and launch your project!
* Sass for CSS
* Javascript compilation and minification
* Browsersync to preview your work

## Get started: Use This Template

<details open>
 <summary>Right from this README</summary>
 
###  Create a new project using zero_point_shopify and add it to your GitHub account

 [Click here to use this template](https://github.com/MWDelaney/zero_point_shopify/generate)
 </details>

<details>
 <summary>With GitHub CLI (https://cli.github.com)</summary>

### Get started from your command line

 ```sh
  gh repo create example.com --template MWDelaney/zero_point_shopify
 ```

</details>

## Get to Know zero_point_shopify

Ready to go deeper? Here's how zero_point_shopify is laid out:

```sh
example.com                 # β Root of your zero_point_shopify-based project
βββ src/                    # β Source directory
β   βββ assets/             # β Site assets
β   β   βββ fonts/
β   β   βββ images/
β   β   βββ scripts/
β   β   βββ styles/
β   β   βββ views/
β   β       βββ layouts/
β   β       βββ partials/
β   βββ config/             # β Eleventy configuration
β   β   βββ collections.js  # β Add and configure collections (https://www.11ty.dev/docs/collections/)
β   β   βββ filters.js      # β Add and configure filters (https://www.11ty.dev/docs/filters/)
β   β   βββ passthroughs.js # β Add and configure passthroughs (https://www.11ty.dev/docs/copy/)
β   β   βββ plugins.js      # β Add and configure plugins (https://www.11ty.dev/docs/plugins/)
β   β   βββ shortcodes.js   # β Add and configure shortcodes (https://www.11ty.dev/docs/shortcodes/)
β   β   βββ templateLanguages.js   # β Configure custom template languages (HINT: this is where zero_point_shopify's Sass and Javascript pipelines are set up!) (https://www.11ty.dev/docs/languages/custom/)
β   β   βββ watchtargets.js # β Add and configure watch targets (https://www.11ty.dev/docs/watch-serve/)
β   βββ data                # β Customize site data (https://www.11ty.dev/docs/data/)
β   β   βββ navigation.json # β Site navigation configuration
β   βββ pages               # β Add "pages" collection items here
β       βββ index.md        # β Default index page
β       βββ pages.json      # β Shared pages attributes
βββ .eleventy.js            # β Core Eleventy config file
βββ netlify.toml            # β Netlify deployment and plugin configuration (optional)
βββ README.template.md      # β zero_point_shopify readme
βββ README.md               # β Your project's readme (automatically generated when this template is used)
```

## Eleventy Configuration

Eleventy configuration is abstracted from the typical `.eleventy.js` file and moved to `/src/config/` for easy organization and configuration of collections, filters, passthroughs, etc.

## Install project dependencies

```bash
npm i
```

## Run the project locally

```bash
npm run start
```

## Build for production

```bash
npm run production
```
