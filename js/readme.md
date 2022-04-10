## Conventions

* ESNext
* composition through ES modules and functions
* guard clauses over if
* pattern matching where possible (especially destructuring assignment)
* const over let (remember, `const obj = {}` is a trap)
* [never use semicolons](https://feross.org/never-use-semicolons/)
* ESLint
* Vite for hmr and [esbuild](https://github.com/evanw/esbuild) 
* Tests with vitest, jsdom, msw

## Anti-patterns

* Typescript is cargo cult of the system programming world which reduces maintainability. Correct strong types in browser is Rust code compiled to wasm.
* [Classes over Modules with functions](https://dev.to/bytebodger/replacing-javascript-classes-with-the-module-design-pattern-48bl)

