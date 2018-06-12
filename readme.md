# Testing Vue Laracasts Code Along

## 1

## 2

## 3

Add a watcher via `package.json`:

```json
"watch": "mocha-webpack --webpack-config webpack.config.js *--watch* --require test/setup.js test/*.spec.js"
```

Run via:

```bash
npm run watch
```

Set up the world via:

```js
wrapper.setData({ count: 5 });
```

Check element style via:

```js
.hasStyle('property', 'value')
```

You must also assert that the style is true or false, e.g.:

```js
expect(wrapper.find('p').hasStyle('color', 'pink')).toBe(true);
```

Can `isVisible()` can be used in the new version?