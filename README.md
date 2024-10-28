# portfolio

(=^･ｪ･^=))ﾉ彡 ☆ hi!

This is a personal portfolio web application built using React and TypeScript, styled with CSS, and integrated with Sanity.io as a CMS for managing blog posts. The project is powered by Vite for a quick development experience.

## tech stack

-   React:
    -   JavaScript library for building the user interface.
-   TypeScript:
    -   Adds static typing to JavaScript, improving code quality and developer experience.
-   CSS:
    -   Custom styling for layout and appearance.
-   Sanity.io:
    -   Content management system used to manage and display blog posts.
-   Vite:
    -   Next-generation front-end tooling that provides fast bundling and optimized build for development and production.

## project structure

The project is organized as follows:

```
portfolio/
├── public/                  # Static assets
├── src/
│   ├── components/          # Reusable UI components
│   ├── pages/               # Main page components
│   ├── styles/              # CSS files for styling
│   ├── utils/
│   │   └── sanity/          # Sanity client setup for fetching data
│   └── App.tsx              # Main application component
└── README.md                # Project documentation
```

## setup

1. clone the repo:

```zsh
git clone https://github.com/xdaybreakerx/portfolio.git
cd portfolio
```

2. install dependencies:

```zsh
npm install
```

3. (optional) link to Sanity project with their [getting started guide.](https://www.sanity.io/docs/getting-started-with-sanity)

4. run the app:

```zsh
npm run dev
```

The application should now be running at http://localhost:5173

## deployment

You can deploy this application using services like Netlify, Vercel, or GitHub Pages. 

## license

This project is licensed under the MIT License.
