<!-- Add banner here -->

# Monorepo

![Random GIF](https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif)

- [Monorepo](#project-title)
- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)

# Installation

```
1. install Nodejs 16
2. npm ci
```

# Usage
```
* Edit compiler.json, for example:

  "demo": {
    "server": {
      "index": "/src/packages/demo/index.ts"
    }
  }

```

# Development

```
* with nodemon
npm start source="demo" exec="index"
```
```
* without nodemon
npm start source="demo"

* and run project manually
node dist/demo/index.js
```
# Production
```
npm run build source="demo"
```