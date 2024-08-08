# scratch-gui

This repo is a copy of Scratch's editor modified for Snazzle

To open the current build in your browser on Github Pages:

https://elip100.github.io/scratch-gui/

## Contributing (please read)
1. Fork ___ALL BRANCHES___ of the repo
2. Make changes to the `develop` branch
3. Create a build ([instructions here](#creating-a-build))
4. Run `npm run deploy` ___in a Bash terminal___ (Git Bash works fine on Windows)[^1]
6. Commit changes & make a pull request

## Run locally
1. Clone the repo
2. run `npm install`
3. run `npm start`

## Creating a build
To compile the editor to vanilla javascript, run `npm run build`. The output will be in the `build` folder.
The latest built version can be found on the `gh-pages` branch.

[^1]: All this really does is replace the contents of the `gh-pages` branch with the contents of the `build` folder. If you have issues with this step, you can do it manually.
