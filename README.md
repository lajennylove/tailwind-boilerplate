<p align="center">
  <a href="https://tailwindcss.com" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-light.svg">
      <img alt="Tailwind CSS" src="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-light.svg" width="350" height="70" style="max-width: 100%;">
    </picture>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/lajennylove/tailwind-boilerplate" alt="License">
  <img src="https://img.shields.io/github/repo-size/lajennylove/tailwind-boilerplate" alt="Repo Size">
  <img src="https://img.shields.io/github/stars/lajennylove/tailwind-boilerplate?style=social" alt="Stars">
</p>
---

# TailwindCSS/VanillaJS/GulpJS boilerplate.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://repository-images.githubusercontent.com/621943502/80cd6dcb-93a9-4352-a2bd-722aabab1452">
    <source media="(prefers-color-scheme: light)" srcset="https://repository-images.githubusercontent.com/621943502/80cd6dcb-93a9-4352-a2bd-722aabab1452">
    <img alt="Tailwind CSS boilerplate" src="https://repository-images.githubusercontent.com/621943502/80cd6dcb-93a9-4352-a2bd-722aabab1452" width="450" height="auto" style="max-width: 100%;">
  </picture>
</p>

This Tailwind CSS Boilerplate provides an easy and efficient way to incorporate Tailwind CSS into your gulp workflow. The boilerplate includes support for transpiling your custom classes to the main app.css file with SASS, and allows you to unify all of your JavaScript libraries into just one app.js file that's compiled and minified.

In addition, the boilerplate includes automatic image optimization and minification by dropping images into the ./src/img/ folder. We've also included the SVG Store library, which enables you to unify all of your SVGs into just one file that can be used with the <use> tag.

Finally, you'll enjoy hot reloading on changes with BrowserSync, which allows you to see your changes instantly without having to manually reload your browser. With these features, this Tailwind CSS Boilerplate provides a powerful and efficient foundation for your web development projects.

## VISIT THE BOILERPLATE

Here you can visit the current boilerplate.
https://lajennylove.github.io/tailwind-boilerplate/

## HOW TO USE:

1. clone the repo `git clone https://github.com/lajennylove/tailwind-boilerplate.git`
2. `cd tailwind-boilerplate` to enter the project's folder
3. `npm install` or `yarn` to install all your npm node_modules
4. Then to start the project in your `npm start` or `yarn start` to start the live server
5. Visit with your browser `http://localhost:3008` to view your project with hot reload support
6. Open with your console the project using VS Code typing `code .` then open your `dist/index.html` and start coding
7. To build to production you just need to do `npm build` or `yarn build` and all the CSS and JS files wil be minified.

## DIRECTORY STRUCTURE:

```
tailwind-boilerplate/   # Base directory for your installation
├── dist/               # Built application assets
│ ├── css/              # CSS file generated by Gulp
│ ├── js/               # JS file generated by Gulp
│ └── img/              # IMG's generated by Gulp
├── src/                # Uncompiled source assets as images, JavaScript files or SCSS files.
│ ├── css/              # Your scss files
│ ├── js/               # Your js files
│ └── img/              # Your images(jpg, png, svg) files
├── gulpconfig.json     # Here you can change paths and gulp settings
├── gulpfile.babel.js   # Main GulpJS file
├── package.json        # Your Node package admin file
└── tailwind.config.js  # Here you can change the Tailwind CSS settings
```

## Resources

To create this template I used the following resources:

- [Stefan Stankovic](https://github.com/stefansdev/creativdepot)
- [David Grzyb](https://github.com/davidgrzyb)
- [Meraki UI](https://merakiui.com/)
- [Tailwind CSS](https://tailwindcss.com)
- [Unsplash](https://unsplash.com)
- [AlpineJS](https://alpinejs.dev)
- [ShieldsIO](https://shields.io/)

## Author comments

I strongly recomend to delete all the body contents (besides the app.js at the bottom) and start following a video tutorial like the list I left below:

- https://www.youtube.com/watch?v=L6Jwa7al8os&list=PLg9gWbGC0zdADkKA0sgkeoJiGSa9xwtoj

✨ Happy coding! ✨

For any questions contact @lajennylove at github
