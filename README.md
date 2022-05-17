
# Boilerplate and Starter for Next JS 12+, Tailwind CSS 3 

A brief description of what this project does and who it's for


## Feature

Developer experience first:


- ⚡ [Next.js](https://nextjs.org/) for Static Site Generator

- 💎 Integrate with [Tailwind CSS](https://tailwindcss.com/)

- ✅ Strict Mode for TypeScript and React 18

- 📏 Linter with [ESLint](https://eslint.org/) (default NextJS, NextJS Core Web Vitals, Tailwind CSS and Airbnb configuration)

- 💖 Code Formatter with [Prettier](https://prettier.io/)

- 🦊 Husky for Git Hooks

- 🚫 Lint-staged for running linters on Git staged files

- 🚓 Lint git commit with Commitlint

- 🦺 Testing with Jest and React Testing Library

- 💡 Absolute Imports using @ prefix

- 🗂 VSCode configuration: Debug, Settings, Tasks and extension for PostCSS, ESLint, Prettier, TypeScript, Jest

- 🤖 SEO metadata, JSON-LD and Open Graph tags with Next SEO


- [⚙️ Bundler Analyzer](https://www.npmjs.com/package/@next/bundle-analyzer)

- 🖱️ One click deployment with Vercel or Netlify (or manual deployment to any hosting services)

- 🌈 Include a FREE minimalist theme

- 💯 Maximize lighthouse score

- Built-in feature from Next.js:

- ☕ Minify HTML & CSS

- 💨 Live reload

- ✅ Cache busting


## Philosophy

- Minimal code

- SEO-friendly

- 🚀 Production-ready


## Requirements

- Node.js 14+ and npm


## Getting started
  
  Run the following command on your local environment:


    git clone --depth=1 https://github.com/solutelabs/nextjs-boilerplate.git my-project-name
    cd my-project-name
    npm install

Then, you can run locally in development mode with live reload:

    npm run dev

Open [http://localhost:3000](http://localhost:3000) with your favorite browser to see your project.

    .
    ├── README.md                       # README file
    ├── __mocks__                       # Mocks for testing
    ├── .github                         # GitHub folder
    ├── .husky                          # Husky configuration
    ├── .vscode                         # VSCode configuration
    ├── public                          # Public assets folder
    ├── src
    │   ├── layouts                     # Layouts components
    │   ├── pages                       # Next JS Pages
    │   ├── pages.test                  # Next JS Pages tests (this avoid test to treated as a Next.js pages)
    │   ├── styles                      # Styles folder
    │   ├── templates                   # Default template
    │   └── utils                       # Utility functions
    ├── tailwind.config.js              # Tailwind CSS configuration
    └── tsconfig.json                   # TypeScript configuration

## Customization
- You can easily configure Next js Boilerplate. Please change the following file:

- public/apple-touch-icon.png, public/favicon.ico, public/favicon-16x16.png and public/favicon-32x32.png: your website favicon, you can generate from [https://favicon.io/favicon-converter/](https://favicon.io/favicon-converter/)

- `src/styles/global.css`: your CSS file using Tailwind CSS

## Deploy to production
 You can see the results locally in production mode with:

    $ npm run build
    $ npm run start


The generated HTML and CSS files are minified (built-in feature from Next js). It will also removed unused CSS from [Tailwind CSS](https://tailwindcss.com/).

## Testing


 All tests are colocated with the source code inside the same directory. So, it makes it easier to find them. Unfortunately, it is not possible with the pages folder which is used by Next.js for routing. So, what is why we have a pages.test folder to write tests from files located in pages folder.

## Deploy to Vercel
The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Learn More
To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.

- [Learn Next.js](https://nextjs.org/learn/foundations/about-nextjs) - an interactive Next.js tutorial.


## VSCode information (optional)

If you are VSCode users, you can have a better integration with VSCode by installing the suggested extension in `.vscode/extension.json`. The starter code comes up with Settings for a seamless integration with VSCode. The Debug configuration is also provided for frontend and backend debugging experience.


With the plugins installed on your VSCode, ESLint and Prettier can automatically fix the code and show you the errors. Same goes for testing, you can install VSCode Jest extension to automatically run your tests and it also show the code coverage in context.

Pro tips: if you need a project wide type checking with TypeScript, you can run a build with `Cmd` + `Shift` + `B` on Mac.

## Contributions

 Everyone is welcome to contribute to this project. Feel free to open an issue if you have question or found a bug.


