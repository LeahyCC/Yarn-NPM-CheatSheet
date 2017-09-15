# Yarn-NPM-CheatSheet
YarnJS -  What you need to know

https://github.com/yarnpkg/yarn
https://yarnpkg.com/en/docs/

Basic use

installed it with `npm i -g yarn`
- `yarn --version`
Test that Yarn is installed
- `yarn init`
Will start the proccess of creating package.json and the yarn.lock files
- `yarn add packagename`
The package is saved to your dependancies package.json
- `yarn remove packagename`
The package is removed from your dependancies package.json
- `yarn add packagename --dev`
The package is saved to your dev dependancies package.json
- `yarn upgrade`
- `yarn upgrade-interactive`
Allows you to selectively upgrade specific packages in a simple way
- `yarn`
Checks the lockfile and updates or downgrades packages (source control)

- `yarn link`
- `yarn outdated`
- `yarn publish`
- `yarn run`
- `yarn cache clean`
- `yarn login`
- `yarn test`
- `yarn --production`

- `yarn licenses ls`
Automatically create your license dependency disclaimer
- `yarn why packagename`
Identify why the package is installed, detailing which other packages depend upon it.
