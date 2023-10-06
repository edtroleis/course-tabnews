# Tests

## Install jest test runner

npm install --save-dev jest@29.6.2

## Set scripts

```
"scripts": {
    "dev": "next dev",
    "lint:check": "prettier --check .",
    "lint:fix": "prettier --write .",
    "test": "jest",
    "test:watch": "jest --watch"
  },
```

# Run tssts

```
npm test
npm run test:watch    # watch all tests dynamically
```
