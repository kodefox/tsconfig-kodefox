[![Build Status](https://travis-ci.com/kodefox/tsconfig-kodefox.svg?branch=master)](https://travis-ci.com/kodefox/tsconfig-kodefox)

# TSConfig KodeFox

## Installation

```
yarn add -D tsconfig-kodefox
```

-- or --

```
npm install --save-dev tsconfig-kodefox
```

## Usage

> In tsconfig.json
>
> ```
> {
>   "extends": "tsconfig-kodefox",
>   "compilerOptions": {
>     "jsx": "react",      // or "react-native" depends on your project
>     "typeRoots": ["node_modules/@types"]
>   }
> }
> ```
