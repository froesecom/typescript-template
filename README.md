# Erik's TypeScript Template

Built using Node 11.6

Includes:
- TypeScript
- Jest configured for TS (testing framework)
- ts-node (TypeScript execution for NodeJS)
- Prettier + my config (Code formatting)
- TSLint + config

### To install
- clone repo
- `yarn install`
-  if you want to add new directories, you have to tell typescript where they are by adding them to `tsconig.json` in the `include` block:
~~~
"include": [
	"models/**/*",
	"helpers/**/*",
	"presenters/**/*",
	"__tests__/**/*"
],
~~~

### To run
- `yarn test` to run tests
- `yarn type-check` to type-check all files
- `yarn hello` to run "Hello World" script
