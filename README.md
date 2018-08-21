# [Grunt](https://gruntjs.com/) Installation Instructions
Grunt is a JavaScript task runner, a tool used to automatically perform frequent tasks such as minification, compilation, unit testing, and linting.

## Getting Ready
* verify node is installed, can do `node -v` to check version, if doesn't error we are good.
* update npm to latest version `npm update -g npm`
* create a directory for you project and cd into it.
* once in your directory install grunt-cli `npm install -g grunt-cli`

### Install Required Apps for Image Minification
* Download and install [graphicsmagick](http://www.graphicsmagick.org/download.html)
* Download and install [ghostscript](https://www.ghostscript.com/download/gsdnld.html)
* Download and install [imagemagick](https://www.imagemagick.org/script/download.php) Make sure to check the option 'Install legacy utils'
* On windows. Install `gm` with `npm install -g gm`
* Restart system

## Clone the Repo
* Clone `git clone https://github.com/eldar996/grunt`
* Run `npm install` to install all required packages from package.json file
* Run grunt to start minification by `grunt` if task is default or `grunt responsive_images`
