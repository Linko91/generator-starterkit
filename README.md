# generator-starterkit 

[![Build Status](https://img.shields.io/travis/carloscuesta/generator-starterkit.svg?style=flat-square)](https://travis-ci.org/carloscuesta/generator-starterkit)
[![Dependency Status](http://img.shields.io/david/carloscuesta/generator-starterkit.svg?style=flat-square)](https://david-dm.org/carloscuesta/generator-starterkit)
[![DevDepencies Status](https://img.shields.io/david/dev/carloscuesta/generator-starterkit.svg?style=flat-square)](https://david-dm.org/carloscuesta/generator-starterkit#info=devDependencies)

![yo-starterkit](https://cloud.githubusercontent.com/assets/7629661/10104170/6d3f83aa-63a8-11e5-9954-4a051aef344b.png)

> Yeoman generator that scaffolds out my front end development [starterkit](https://github.com/carloscuesta/starterkit).

## Technologies

- [**Gulp**](http://gulpjs.com): Automate and enhance your workflow.
- CSS Preprocessors
    - [**Sass**](http://sass-lang.com): CSS with superpowers.
    - [**Less**](http://lesscss.org): Less extends CSS with dynamic behavior.
- Templating / Markup
    - [**Jade**](http://jade-lang.com): Templating engine.
    - [**Html**](https://developer.mozilla.org/es/docs/Web/HTML)
- [**Babel**](https://babeljs.io): Use next generation JavaScript, today.

## Requirements and Use

### Requirements

- [NodeJS](https://nodejs.org/en/)
- [Yeoman](http://yeoman.io)
- [Generator-Starterkit](https://github.com/carloscuesta/generator-starterkit)

```bash
$ npm install -g yo
$ npm install -g generator-starterkit
```

### Use

Before running the generator you will need to **create a folder** for your project where the generator will create all the project files and directories.

```bash
$ mkdir project
$ cd project
```

Once you have, **NodeJS**, **Yeoman**, **generator-starterkit** installed and your project folder created you can run the generator using:

```bash
yo starterkit
```

_Now the [generator-starterkit](https://github.com/carloscuesta/generator-starterkit) will start to ask some questions to setup the project for you; project information, technologies and languages that you want to use and will install the dependencies automatically based on your decisions. 

Also there are a lot of files being created dynamically such as gulp.js, package.json, readme.md, styles and templates to match the technologies and options that you choose from the generator. (See the [technologies available](https://github.com/carloscuesta/generator-starterkit#technologies) above.)_

## Features

```**styles**```: [Sass](http://sass-lang.com) / [Less](http://lesscss.org) auto compiling, prefixing and minifiying.
```**templates**```: [Jade](http://jade-lang.com) / Html auto compiling and minifiying.
```**scripts**```: Scripts concatenation, transpiling with [Babel](https://babeljs.io) and minifiying.
```**images**```: Images optimization.
```**deploy**```: Deploying your project into a ftp server.
```**beautify**```: Beautify preproduction files.
```**browsersync**```: Automatically injects all your changes in ```styles```, ```templates``` and ```scripts``` into your browser and other devices on save.

For more documentation about gulp workflow / tasks go to [starterkit gulp tasks](https://github.com/carloscuesta/starterkit#tasks)

## Options

- ```--skip-install```: Skips the installation of dependencies with npm.
- ```--skip-welcome-message```: Skips the welcome message.
- ```--skip-install-message```: Skips the message after the installation of dependencies.
- ```--skip-cache```: o not remember prompt answers.

## License

The code is available under the [MIT](https://github.com/carloscuesta/generator-starterkit/blob/master/LICENSE) license.
