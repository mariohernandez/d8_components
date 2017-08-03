# Component Driven Development
### Local environment setup

In order to follow along in the Component Driven Development workshop, please ensure the following setup is complete prior to starting the workshop.

## The Tools
* [Homebrew](https://brew.sh/): Package manager for OSx
* [NodeJS](https://nodejs.org/en/): For plugins and development tools
* [NPM](https://www.npmjs.com/):  To manage all node dependencies/packages
* [Gulp](https://gulpjs.com/): To automate many of the development taks we will perform
 to work properly.
[NVM](https://github.com/creationix/nvm): To manage version of Node across projects.
* [KSS Node](https://github.com/kss-node/kss-node/wiki/Quick-Start-Guide): To generate the styleguide
* [Yeoman](http://yeoman.io/):  To create a project scaffolding using ...
* [Mediacurrent's theme generator](https://github.com/mediacurrent/theme_generator_8).

## Installing the tools
1. Install and configure Homebrew if you are using a Mac (recommended):
`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
* Ensure homebrew is up to date by running `brew update`
* To make sure your system is ready to brew, run `brew doctor`
* Add Homebrew's location to your $PATH in your `.bash_profile` or `.zshrc` file by running `export PATH="/usr/local/bin:$PATH"`

2. Install NodeJS and NPM.  NPM will be installed with Node.
* `brew install node`

3. Install Gulp globally
* `npm install gulp-cli -g`
* `npm install gulp -D`

4. Install and configure NVM to manage node versions
* `curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash`
* Edit your machine's profile on either `~/.bash_profile`, `~/.zshrc`, `~/.profile`, or `~/.bashrc` by pasting the following in one of those files above:
* `export NVM_DIR=~/.nvm` if not already there.

5. Intall KSS Node to generate the styleguide
* `npm install --save-dev kss`

6. Install Yeoman and Mediacurrent's Theme Generator to be able to generate our theme later
* `npm install -g yo generator-mc-d8-theme`


### That should do it.

## Windows Users
1. [Install NodeJs and NPM](http://blog.teamtreehouse.com/install-node-js-npm-windows)
2. [Install Gulp](https://gist.github.com/objarni/2ece180ddb69eb71564e)
3. [Intall NVM](https://github.com/coreybutler/nvm-windows)
4. [Install Yeoman](http://yeoman.io/codelab/setup.html)



