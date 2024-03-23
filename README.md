# HooBank

Web application to demonstrate React.js and Tailwind CSS framework.

Deployed Site: [ConnorXCX.github.io/HooBank](https://ConnorXCX.github.io/HooBank/)

References:

1. [Build and Deploy a Fully Responsive Website with Modern UI/UX in React JS with Tailwind](https://youtu.be/_oO4Qi5aVZs?si=FVXgFZiUStjwHCMJ)

Commands to Run Locally:

1. `npm install`
2. `npm run dev`

How to Configure GitHub Pages Dependency:

1. Add `base` parameter to `vite.config.js`
2. Add `homepage` parameter to `package.json`
3. Add `predeploy` parameter with `npm run build` under `scripts` in package.json
4. Add `deploy` parameter with `gh-pages -d dist` under `scripts` in package.json
5. `npm install gh-pages --save-dev`

Command to Deploy to GitHub Pages:

1. `npm run deploy`
