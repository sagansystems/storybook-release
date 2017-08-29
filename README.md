# storybook-release

This is a version of `@storybook/react` that works with Inferno by including aliases in the webpack config file for `react` and `react-dom` to `inferno-compat`. We could not do a release in our own sagansystems/storybook repo because storybook pushes directly to NPM, so this is a workaround.
