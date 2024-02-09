```
$ npm ci
$ npx postcss input.css
TypeError: (intermediate value)(intermediate value)(intermediate value).replace is not a function
    at ./node_modules/tailwindcss/lib/lib/collapseAdjacentRules.js:37:149
    at Array.every (<anonymous>)
    at ./node_modules/tailwindcss/lib/lib/collapseAdjacentRules.js:37:35
    at Root.each (./node_modules/postcss/lib/container.js:53:16)
    at collapseRulesIn (./node_modules/tailwindcss/lib/lib/collapseAdjacentRules.js:24:14)
    at ./node_modules/tailwindcss/lib/lib/collapseAdjacentRules.js:59:9
    at ./node_modules/tailwindcss/lib/processTailwindFeatures.js:61:53
    at async plugins (./node_modules/tailwindcss/lib/plugin.js:38:17)
    at async LazyResult.runAsync (./node_modules/postcss/lib/lazy-result.js:261:11)
    at async Promise.all (index 0)
```
