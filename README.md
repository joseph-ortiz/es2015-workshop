# ES2015 Workshop

All changes should be made to the setup code. No changes should be made to the
expectation line.

## Setup

- `git clone git@github.com:paulelliott/es2015-workshop.git`
- Install node 0.12+ or iojs
- `npm install`
- `npm test`
- You should see a friendly message from mocha showing all tests failing

## Section 1 - Variables

`npm test test/variables.js`

- let
- const

## Section 2 - Strings

`npm test test/strings.js`

- interpolation
- template strings
- new String methods via polyfill
  - startsWith
  - endsWith
  - includes
  - repeat
  - trim

## Section 3 - Functions

`npm test test/functions.js`

- fat arrows
- single line functions with implicit returns
- default parameters
- spread

## Section 4 - Enhanced Object Literals

`npm test test/object-literals.js`

- shorthands
- methods
- dynamic property names
