# Pokémon GameBoy CSS

Inspired by: https://github.com/nostalgic-css/NES.css

This is a joke CSS-framework and it is not intended for use in production. You can [see a demo here](https://luttje.github.io/css-pokemon-gameboy/). The demo performs poorly on mobile devices or small resolutions.

## Usage

To efficiently use this repository it is recommended you use [npm and grunt](https://gruntjs.com/getting-started) to automatically compile the files to a distribution. Check the [releases section on GitHub](https://github.com/luttje/pokemon-gameboy-css/releases) for pre-compiled distributions.

#### Using the distribution

1. Copy all the files in the `dist` directory to your project
2. Append the following includes in the body of the page the utilize this style:

```html
<link rel="stylesheet" href="./styles/pokemon-gameboy-css.css">
```

3. See the demo.html or .scss-files for all possible classes and effects.

#### To compile it yourself

1. Run `npm install`in the root directory (the directory where `package.json` is located)

2. Run `grunt` in the root directory to build a distribution

   -OR-

3. Run `grunt watch` in the root directory to watch for changes in the `src` directory and automatically build new distributions.

Use [this technique described by Coby Chapple](https://gist.github.com/cobyism/4730490) to quickly push an update to the github pages branch.

## Licenses

**The images in this repository are the property of Nintendo. The style is also property of Nintendo.**

The code in this repository is Unlicensed, with the exception of used third-party libraries like Grunt, Node and npm. You can view the licenses related to third-parties in the root of the source-code or on their respective websites.
