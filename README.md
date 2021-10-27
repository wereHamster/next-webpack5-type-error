1. Clone this repo
2. `npm install`
3. `./node_modules/.bin/tsc`

Output:

```
$ ./node_modules/.bin/tsc 
node_modules/next/dist/server/config-shared.d.ts:1:15 - error TS2724: '"next/dist/compiled/webpack/webpack"' has no exported member named 'webpack5'. Did you mean 'webpack'?

1 import type { webpack5 } from 'next/dist/compiled/webpack/webpack';
                ~~~~~~~~


Found 1 error.
```