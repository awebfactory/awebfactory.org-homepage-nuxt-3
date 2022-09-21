# AWebFactory.org. The Making of. From Scratch. Step-by-Step

> <small>[see [below](#content-wind) for details of @Atinux/content-wind template, upon which AWebFactory.org was originally based]</small>

## Code as single source of truth

(Building and) learning process: Clone the repo and follow the commits step by step. Run in dev mode and compare what you are seeing happen with the code and the changes for each commit. We try to make them as atomic as possible.

```bash
git clone https://github.com/awebfactory/awebfactory.org-homepage-nuxt-3.git
cd awebfactory.org-homepage-nuxt-3
npm install
npm run dev
```

- See this project on AWebFactory dot org (`coming soon`) to see
  - mvp and log of where we're coming from
  - log of where we are
  - mvp of where we're going.
- See [commits](https://github.com/awebfactory/awebfactory.org-homepage-nuxt-3/commits/main) to see where we are and where we've come from.
- The [Git Book](https://git-scm.com/book/en/v2) explains [how to check out different commits](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)
- See the `package.json` file for dependencies
- See the [Nuxt 3 docs](https://v3.nuxtjs.org/) for anything else

---

<small>...originally based on [Content Wind template by @Atinux](https://github.com/Atinux/content-wind)

## Content Wind

A lightweight Nuxt template to write a Markdown driven website, based on [Nuxt Content](https://content.nuxtjs.org), [TailwindCSS](https://tailwindcss.com) and [Iconify](https://iconify.design).

- [Demo & Docs](https://content-wind.nuxt.dev)
- [Play online](https://stackblitz.com/github/Atinux/content-wind?file=content%2F1.index.md)

### Features

- [Document-Driven Mode](https://content.nuxtjs.org/guide/writing/document-driven)
  - Create pages in Markdown in the `content/` directory
  - Use Nuxt layouts in your Markdown pages
  - Enjoy meta tag generation from Markdown files
  - Generated navigation based on your pages
- Switch between Light & Dark mode :moon:
- Access 100,000 icons from 100+ icon sets with the [`<Icon>` component](https://github.com/Atinux/nuxt-icon)
- Highlight code blocks with [Shiki](https://shiki.matsu.io)
- Create Vue components and use them in your Markdown
- Deploy on any Node or Static hosting: GH Pages, Vercel, Netlify, Heroku, etc.

### Usage

Take a look at [content-wind.nuxt.dev](https://content-wind.nuxt.dev) for the complete documentation.

### Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install
```

### Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

### Deployment

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FAtinux%2Fcontent-wind) [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Atinux/content-wind)


#### Static Hosting

Pre-render the website to be deployed on any static hosting:

```bash
npm run generate
```

The `dist/` directory is ready to be deployed (symlink to `.output/public`), [learn more on Nuxt docs](https://v3.nuxtjs.org/guide/deploy/static-hosting).

#### Node server

Build the application for production:

```bash
npm run build
```

Start the server in production:

```bash
node .output/server/index.mjs
```

Learn more on [Nuxt docs](https://v3.nuxtjs.org/guide/deploy/node-server) for more information.
