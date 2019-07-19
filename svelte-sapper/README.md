# Svelte / Sapper Beginners
_session by Jörn (@NarigoDF)_

- [Svelte Homepage](https://svelte.dev/)
- [Sapper Homepage](https://sapper.svelte.dev/)

Basically a run through the Sapper template and a few key concepts of Svelte.

Svelte is a compiler for components/declarative coding and does not need a
virtual dom anymore since the compiler creates the necessary means to manipulate
the dom directly.

1. Use `npx degit` to get the SAPPER template by shallow cloning a git
   repository
2. Install all packages with `npm i`
3. Checked `package.json` scripts: `dev` for live reloading, `test` for cypress
   testing, `export` for creating a static site
4. `src/routes/\_layout.svelte` containing the base layout and getting `segment`
   variable injected as prop.
5. Actually `export let myProp` in scripts are like React props
6. Using `<slot></slot>` to add children
7. CSS styles are scoped by default
