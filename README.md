# Diamonds Web Dev Workshop

To make sure that this tutorial works for you, you need to have `node` and its respective package manager `npm` installed. If you haven't already, install both [here](https://github.com/nvm-sh/nvm#install--update-script) using `nvm` (node version manager).

Overview of workshop:

- What is the web? The original [website](http://info.cern.ch/)
- [DNS](https://www.youtube.com/watch?v=UVR9lhUGAyU)
- What do web developers try to achieve/what problems do they solve?
- How does anything I'm doing relate to research?
- HTML, CSS & Javascript.
- [Case study A](https://motherfuckingwebsite.com/) & [Case study B](https://thebestmotherfucking.website/)
- Markdown
- [What is Tailwind](https://www.youtube.com/watch?v=mr15Xzb1Ook)
- [10mins to make the ugliest website possible](https://play.tailwindcss.com/)
- [What is React](https://www.youtube.com/watch?v=Tn6-PIqc4UM)
- SEO & Where the money is.
- [NextJS](https://www.youtube.com/watch?v=Sklc_fQBmcs)
- Finally we get to create a website/load one up. This repo itself contains the starter code for a NextJS application with Tailwind  setup.
- Deploying the website via [Vercel](https://vercel.com/).

Useful links:
- [Semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [Learn more about the Web](https://web.dev/)
- [Learn more about CSS](https://css-tricks.com/)
- [Markdown](https://www.markdownguide.org/cheat-sheet/)
- [React](https://reactjs.org/)
- [Next-JS](https://nextjs.org/)
- [Tailwind](https://tailwindcss.com/)
- [MDX](https://mdxjs.com/)

## Installation

```bash
npm install
```

## Development

First, run the development server:

```bash
npm start
```

or

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

### How to navigate the directories. 

- The pages directory contains the routes to your webpage. `index.js` is `/`. `blog.js` is `/blog`. `404.js` is `/404`. You can see how this goes...
- The `data` directory contains high level information about this blog website. `data/blog` contains all the markdown files used to create the blog. `siteMetadata.js` contains some information that you need to fill out. `projectsData.js` contains the data you need to fill out for the `/projects` page. 
- If you don't like the look of your blog pages/homepage 99% of the logic is governed by the `/layouts` directory. `layouts/AuthorLayout.js` contains the layout of the index page. Other layouts relate to blog posts or the way that blog posts are listed.
- *DO NOT TOUCH `node_modules`* it is a bottomless pit of packages.