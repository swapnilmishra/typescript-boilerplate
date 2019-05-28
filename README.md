# Typescript boilerplate

After getting a bit frustrated in setting up typescript project that includes very basic things required for starting up a typescript project, I decided to give it a go. Although I had to cross-reference many different resources but it was easy enough in the end. This boilerplate contains:

- Typescript compilation - `yarn build`
- Jest for tests - `yarn test`
- Debugging tests and program using VScode - `see below for debugging guide`

## Debugging guide using VScode

- `tests` - go to debugger view in vscode(Cmd+Shift+D on mac), there you can find `Jest All` or `Jest Current file` as launch tasks. Put your debug point in anywhere in `index.test.js` and hit play button.

- `program` - go to debugger view((Cmd+Shift+D on mac)) and use `Debug Program` task and hit play button.
