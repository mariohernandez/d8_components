# Component Driven Development
The component-driven development workshop focuses on 3 areas:
1. Building components in Twig using a living styleguide.
2. Prepping Drupal environment in preparation for component integration.
3. Integrate components with Drupal.

These three areas are covered in my blog series "[Integrating Components with Drupal](https://www.mediacurrent.com/blog/integrating-components-drupal-8-part-1)".
The workshop will use many of the techniques and approaches on the blog series with updates based on latest best practices.

### Local environment setup

In order to follow along in this workshop, please ensure the following setup is complete prior to starting the workshop.

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

## Compiling Sass, Javascript and Styleguide
1. Navigate to `docroot/themes/custom/theme-name`

2. Run `npm install`

3. Run `nvm install`

4. Run `npm run build`

## Other commands you can run
* `npm run compile`: Will compile Sass only

* `npm run styleguide`: Will compile styleguide only

* `npm run compress`:  Will compress assets


## Disable Drupal 8 Caching
This is necessary to properly debug and inspect drupal pages.
* https://www.drupal.org/node/2598914

## Drupal Modules
Install and enable the following modules:
* [Devel and Kint](https://www.drupal.org/project/devel)
* [Paragraphs](https://www.drupal.org/project/paragraphs)
* [Components Libraries](https://www.drupal.org/project/components)

#### Theme
This theme includes Featured Sponsors component along with sub components.
![Featured Sponsors Component](/badcamp.png "Featured Sponsors Component")

### Styleguide
To view the styleguide navigate to `http://your-local/themes/custom/theme-name/dist/style-guide/`

Components markup can be found under `theme-name/src/components/`



