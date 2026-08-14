# Project Start Checklist

If you already know how to work with TypeScript in KoLMafia, you might still want to use this repository as a template, but the full README will have too much information to easily get started. Here's a more streamlined checklist:

- [ ] Update `package.json` to have the information for the new project. Running `yarn init` might help, but it misses some instances of the URL.
  - [ ] Project name and description
  - [ ] Main script name
  - [ ] Author
  - [ ] Various URLs (repo, issues, and homepage)
- [ ] Update the main entry point in `webpack.config.js`; this should probably be the same as the main script name you put in `package.json`, but without the `.js`.
- [ ] Upgrade dependencies: `yarn upgrade kolmafia@latest libram@latest eslint-plugin-libram@latest`
- [ ] Consider updating the license.
- [ ] Replace the `README.md` file with one appropriate to your project
- [ ] Delete this file.
