![Portfolio Social Preview](./public/og.png)

<p align="center">
    <a aria-label="Hugo's Website" href="https://hrcd.fr">
        <img alt="" src="https://img.shields.io/badge/Website-hrcd.fr-blue?style=for-the-badge&labelColor=000000&logo=google-chrome&logoColor=white">
  <a aria-label="License" href="https://github.com/hugorcd/canvas/blob/main/LICENSE">
    <img alt="" src="https://img.shields.io/npm/l/vue.svg?style=for-the-badge&labelColor=000000&color=blue">
    </a>
  <a aria-label="Follow Hugo on Twitter" href="https://twitter.com/HugoRCD__">
    <img alt="" src="https://img.shields.io/twitter/follow/HugoRCD__.svg?style=for-the-badge&labelColor=000000&logo=twitter&label=Follow%20Hugo&logoWidth=20&logoColor=white">
  </a>
</p>

# Canvas template

Canvas Portfolio is a fully customizable i18n portfolio template built with Nuxt and Nuxt UI, designed to help you showcase your work, testimonials, and key information with ease. The template integrates with Nuxt Studio for a smooth editing experience, while leveraging Nuxt Content for content management. Built with performance, flexibility, and responsiveness in mind, Canvas Portfolio provides a robust foundation for developers and creatives alike.

## Demo

You can see a live demo at [hub.canvas.hrcd.fr](https://canvas.hrcd.fr/).

## Deploy to Nuxthub

[![Deploy to NuxtHub](https://hub.nuxt.com/button.svg)](https://hub.nuxt.com/new?repo=HugoRCD/canvas-nuxthub)

## Features

- **Modern Components & Layouts** – Includes built-in components.
- **Nuxt UI v3** – Utilize pre-built, customizable UI components.
- **NuxtHub ready** - Deploy on NuxtHub in seconds.
- **Tailwind CSS** – A beautiful, responsive design system.
- **Working Contact Form** – Integrated with Resend for easy email handling.
- **Multi-language Support** – Powered by Nuxt i18n.
- **SEO-Ready** – Open Graph Image (Nuxt OG Image) & Nuxt Robots for automatic robots.txt generation.
- **Good practices** – Auto-generated sitemap, optimized images (Nuxt Image), and ESLint (Nuxt config with Flat config).
- **Fully Responsive** – Adapts to all modern browsers and devices.
- **Minimal & Professional Design** – Clean, elegant, and easy to customize.

## Quick Setup

1. Clone this repository if you have access or download it from the store
```bash
git clone git@github.com:HugoRCD/canvas-nuxthub.git
```

2. Install dependencies
```bash
pnpm install
```

3. Copy the `.env.example` file to `.env` and fill in the values
```bash
cp .env.exemple .env
```

4. Start development server
```bash
pnpm dev
```

5. Generate static project
```bash
pnpm generate
```

6. Start production server
```bash
pnpm start
```

## How to Modify the Portfolio Content

This portfolio uses [Nuxt Content](https://content.nuxt.com/) to manage the content. Here's how you can modify it:

First check the `app.config.ts` file to change the global configuration of the portfolio, there is a lot of stuff you can change here.

### Writing

1. Navigate to the `content/2.articles` directory.
2. Here, you'll find Markdown files for each article. To modify an article, simply open its Markdown file and make your changes.
3. To add a new article, create a new Markdown file in this directory. The name of the file will be used as the URL slug for the article.

### Works

1. Navigate to the `content/1.works/` directory.
2. Here, you'll find Markdown files for each article. To modify an article, simply open its Markdown file and make your changes.
3. To add a new project, add a new JSON file in this directory.

#### Featured Works

To change the featured works on the homepage, simply add the `featured: true` key to front matter of the markdown file.

### Other Content

Simply go to the `content/` directory and edit any of the Markdown or JSON files to modify the content.

## Setup the Contact Form

This portfolio uses [Resend](https://resend.com/) to handle the contact form. To set it up, follow these steps:
- Get your api key from [Resend](https://resend.com/) here [your api key](https://resend.com/api-keys)
- Add your api key in the `.env` file
- change the `from` key in the `sendEmail` route in the `server/api/` folder, you can customize everything you want in this route
- That's it, you're good to go!

<!-- automd:fetch url="gh:hugorcd/markdown/main/src/contributions.md" -->

## Contributing
To start contributing, you can follow these steps:

1. First raise an issue to discuss the changes you would like to make.
2. Fork the repository.
3. Create a branch using conventional commits and the issue number as the branch name. For example, `feat/123` or `fix/456`.
4. Make changes following the local development steps.
5. Commit your changes following the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.
6. If your changes affect the code, run tests using `pnpm run test`.
7. Create a pull request following the [Pull Request Template](https://github.com/HugoRCD/markdown/blob/main/src/pull_request_template.md).
   - To be merged, the pull request must pass the tests/workflow and have at least one approval.
   - If your changes affect the documentation, make sure to update it.
   - If your changes affect the code, make sure to update the tests.
8. Wait for the maintainers to review your pull request.
9. Once approved, the pull request will be merged in the next release !

<!-- /automd -->

<!-- automd:fetch url="gh:hugorcd/markdown/main/src/local_development_dev.md" -->

<details>
  <summary>Local development</summary>

- Clone this repository
- Install latest LTS version of [Node.js](https://nodejs.org/en/)
- Enable [Corepack](https://github.com/nodejs/corepack) using `corepack enable`
- Install dependencies using `pnpm install`
- Start development server using `pnpm dev`
- Open [http://localhost:3000](http://localhost:3000) in your browser

</details>

<!-- /automd -->

<!-- automd:contributors license=Apache author=HugoRCD github="hugorcd/canvas-nuxthub" -->

Published under the [APACHE](https://github.com/hugorcd/canvas-nuxthub/blob/main/LICENSE) license.
Made by [@HugoRCD](https://github.com/HugoRCD) and [community](https://github.com/hugorcd/canvas-nuxthub/graphs/contributors) 💛
<br><br>
<a href="https://github.com/hugorcd/canvas-nuxthub/graphs/contributors">
<img src="https://contrib.rocks/image?repo=hugorcd/canvas-nuxthub" />
</a>

<!-- /automd -->

<!-- automd:with-automd lastUpdate -->

---

_🤖 auto updated with [automd](https://automd.unjs.io) (last updated: Mon Feb 10 2025)_

<!-- /automd -->
