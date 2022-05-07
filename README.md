# gen-env

auto generate .env template by scanning source code

[![npm Package Version](https://img.shields.io/npm/v/gen-env)](https://www.npmjs.com/package/gen-env)
[![npm Package Version](https://img.shields.io/npm/dy/gen-env)](https://www.npmtrends.com/gen-env)


## Features
- [x] auto skip some folders
   - node_modules
   - .git
- [x] support multiple file extensions
   - .js
   - .jsx
   - .ts
   - .tsx

## Installation
```shell
npm i -g gen-env
```

## Usage
```
usage: gen-env [dir]

options:
  dir:  optional, default is current directory

examples:
  gen-env
  gen-env ./my-app
```

## License
[BSD-2-Clause](./LICENSE) (Free Open Source Project)
