Repro for https://github.com/storybookjs/storybook/issues/10878

After cloning this repo:

    yarn build-storybook -c storybook

which yields this warning:

    WARN ./storybook/generated-stories-entry.js
    WARN Module Warning (from ./node_modules/eslint-loader/dist/cjs.js):
    WARN
    WARN   Line 1:1:  'use strict' is unnecessary inside of modules  strict
