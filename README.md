# Boilerplate and Starter for Next JS 12+, Tailwind CSS 3 and Javascript

[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=28ADE7&center=true&lines=Modern+Template;Production+ready;Built+your+next+project)](https://git.io/typing-svg)

🚀 Boilerplate and Starter for Next.js, Tailwind CSS and Javascript ⚡️ Made with developer experience first: Next.js, Javascript, ESLint, Prettier, Lint-Staged, VSCode, Netlify, PostCSS, Tailwind CSS.

Clone this project and use it to create your own [Next.js](https://nextjs.org) project.

### Features

Developer experience first:

- 🔥 [Next.js](https://nextjs.org) for Static Site Generator
- 🎨 Integrate with [Tailwind CSS](https://tailwindcss.com)
- 💅 PostCSS for processing Tailwind CSS and integrated to `styled-jsx`
- ✅ Strict Mode for React 17
- ✏️ Linter with [ESLint](https://eslint.org) (default NextJS, NextJS Core Web Vitals, Tailwind CSS configuration)
- 💡 Absolute Imports
- 🛠 Code Formatter with [Prettier](https://prettier.io)
- 🚫 Lint-staged for running linters on Git staged files
- 🗂 VSCode configuration: Debug, Settings, Tasks and extension for PostCSS, ESLint, Prettier, Javascript
- 🤖 SEO metadata, JSON-LD and Open Graph tags with Next SEO
- ⚙️ [Bundler Analyzer](https://www.npmjs.com/package/@next/bundle-analyzer)
- 🖱️ One click deployment with Vercel or Netlify (or manual deployment to any hosting services)
- 🌈 Include a FREE minimalist theme
- 💯 Maximize lighthouse score
- 🧩 Progresive web App

Built-in feature from Next.js:

- ☕ Minify HTML & CSS
- 💨 Live reload
- ✅ Cache busting

### Philosophy

- Minimal code
- SEO-friendly
- 🚀 Production-ready

### Getting things PWA ready

- Create the app [maskable](https://maskable.app/editor) icon
- Generate the icons and [manifest.json](https://www.simicart.com/manifest-generator.html/) files
- publish the app anywhere with [PWA Builder](https://www.pwabuilder.com/
- Check the /layout/Meta for all metadata :)

### Requirements

- Node.js 14+ and npm

### Getting started

Run the following command on your local environment:

```
git clone --depth=1 https://github.com/lertsoft/ my-project-name
cd my-project-name
npm install
```

Then, you can run locally in development mode with live reload:

```
npm run dev
```

Open http://localhost:3000 with your favorite browser to see your project.

```
.
├── README.md                # README file
├── next.config.js           # Next JS configuration
├── public                   # Public folder
│   └── assets
│       └── images           # Image used by default template
├── src
│   ├── layout               # Atomic layout components
│   ├── pages                # Next JS pages
│   ├── styles               # PostCSS style folder with Tailwind
│   ├── templates            # Default template
│   └── utils                # Utility folder
└──  tailwind.config.js       # Tailwind CSS configuration
```

### Customization

You can easily configure Next.tsx Boilerplate. Please change the following file:

- `public/apple-touch-icon.png`, `public/favicon.ico`, `public/favicon-16x16.png` and `public/favicon-32x32.png`: your website favicon, you can generate from https://favicon.io/favicon-converter/
- `src/styles/global.css`: your CSS file using Tailwind CSS
- `src/utils/AppConfig.js`: configuration file
- `src/templates/Main.jsx`: default theme

### Deploy to production

You can see the results locally in production mode with:

```
$ npm run build
$ npm run start
```

The generated HTML and CSS files are minified (built-in feature from Next js). It will also removed unused CSS from [Tailwind CSS](https://tailwindcss.com).

You can create an optimized production build with:

```
npm run build-prod
```

Now, your blog is ready to be deployed. All generated files are located at `out` folder, which you can deploy with any hosting service.

### Deploy to Netlify

Clone this repository on own GitHub account and deploy to Netlify:

[![Netlify Deploy button](https://www.netlify.com/img/deploy/button.svg)

### Deploy to Vercel

Deploy this Next JS Boilerplate on Vercel in one click:

[![Deploy with Vercel](https://vercel.com/button)]

### VSCode information (optional)

If you are VSCode users, you can have a better integration with VSCode by installing the suggested extension in `.vscode/extension.json`. The starter code comes up with Settings for a seamless integration with VSCode. The Debug configuration is also provided for frontend and backend debugging experience.

Pro tips: if you need a project wide type checking with Javascript, you can run a build with <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>B</kbd> on Mac.

### Contributions

Everyone is welcome to contribute to this project. Feel free to open an issue if you have question or found a bug.

### License

Licensed under the MIT License, Copyright © 2022

See [LICENSE](LICENSE) for more information.
