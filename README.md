TDD Workshop
----
詳細は敢えて書きませんのでOwnerに聞いてください。
* Supports Node.js and Python

# Node.js
- node v20.11.1
- npm 10.8.1

## Commands
- `npm install && npm run test` to run tests.
- `NODE_OPTIONS=--experimental-vm-modules npx jest --watch` to run tests on change.

# Python
- Python 3.9
- pipenv

## Setup
```
pip3 install pipenv
pipenv install -d
pipenv shell
```

### Commands
- `pipenv run test` (= python -m unittest)