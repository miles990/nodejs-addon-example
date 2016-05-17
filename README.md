# nodejs-addon-example

### Required

```
npm install -g node-gyp
```

### Build

```
// clone demo
git clone https://github.com/miles990/nodejs-addon-example.git

// build
cd nodejs-addon-example
node-gyp configure
node-gyp build 
```

### Test

```
node test.js
```