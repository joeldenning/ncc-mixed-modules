# ncc-mixed-modules

To see the bug:

```sh
npm install

# Running the project with Node works fine
npm start

# Running the project after building with ncc does not work
npm run build
node dist/index.js # ERROR
```