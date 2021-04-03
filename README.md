# @datawheel/eslint-config

A set of common eslint rules to use on Datawheel javascript projects.

## Usage

You will need to install this package's `peerDependencies` for it to work correctly.
To install both this package and its `peerDependencies` at once, you can use this command:

```bash
npx install-peerdeps --dev @datawheel/eslint-config
```

Check the documentation for the [`install-peerdeps` package](https://www.npmjs.com/package/install-peerdeps) for more options.

To enable this config file, add `"extends": "@datawheel"` to your [eslint config file](https://eslint.org/docs/user-guide/configuring/configuration-files#configuration-file-formats).  
The easiest way is to set it under the `"eslintConfig"` key in the `package.json` file of your project.
