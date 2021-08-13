# ncc-mixed-modules

To see the bug:

```sh
npm install

# Running the source code directly works
npm start

# Running the project after building with ncc does not work
npm run build
node dist/index.js # ERROR
```
