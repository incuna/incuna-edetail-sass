# Requirements
`sass >= 3.3.0.rc.1`

`compass >= 1.0.0.alpha.17`

# Installation
1. `bower install incuna-sass-edetail --save`
2. Add the path to the installed package to your config.rb/Gruntfile.js e.g. `add_import_path = 'lib/incuna-sass'`

# Local checkout
To use a local checkout as your installed version is very easy to do.

1. `git clone -p incuna/incuna-sass-edetail`
1. `cd incuna-sass-edetail`
1. `bower link`
1. `cd project_dir`
1. `bower uninstall incuna-sass-edetail && bower link incuna-sass-edetail`

This creates a symlink to the your checkout allowing you to edit the bower
installed version.

# Releases
To release a new version

1. Increment the version in `bower.json`
2. Edit `CHANGELOG.md` with changes since last release
3. Tag the repository with the version number: e.g. `git tag 2.1.4`
4. Remember to push the tags: `git push --tags`
