# expo-precise-location-permission

Expo native module used to check for precise location permission.

Currently implemented only for iOS.

# API documentation

(async) use:

```
const module = await import(expo-precise-location-permission');
if (module.has()) {
  return true;
}
```

### Add the package to your npm dependencies

1. copy the module to your project sources
2. run `cd path/to/module && npm i && npm run prepare`
3. add `"expo-precise-location-permission": "path/to/module"` to your `package.json`
4. run `npm install`

### Configure for iOS

Run `npx pod-install` after installing the npm package.
