# react-scrabble

> The familiar scrabble word game written in React.js

## Development

1. Getting started


```
cd react-scrabble/
yarn install
yarn run storybook
```

### Scripts

1. `npm run lint` : Lint all js files
2. `npm run lintfix` : fix linting errors of all js files
3. `npm run semantic-release` : make a release. Leave it for CI to do.
4. `npm run storybook`: Start developing by using storybook
5. `npm run test` : Run tests. tests file should be written as `*.test.js` and using ES2015
6. `npm run test:watch` : Watch tests while writing
7. `npm run test:cover` : Show coverage report of your tests
8. `npm run test:report` : Report test coverage to codecov.io. Leave this for CI
9. `npm run build`: transpile all ES6 component files into ES5(commonjs) and put it in `dist` directory
10. `npm run docs`: create static build of storybook in `docs` directory that can be used for github pages

Learn how to write stories [here](https://getstorybook.io/docs/basics/writing-stories)

### License
MIT
