# EsBuildBrowserBundlers
These are custom  EsBuild plugins written in TypeScript for an npm package that can be found [here](https://www.npmjs.com/package/jsmydocs).

Fetch plugin is checking to see if we have already made a request off to npm for whatever import statement is being bundled, and will fetch the file from cache or npm respectively.

Unpkg-path-plugin is generating the url path needed to bundle any external dependencies.

## Dependencies
- [Unpkg](https://www.npmjs.com/package/unpkg)
