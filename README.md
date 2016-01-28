# cv
Exploring ways to display your CV to possible employers

Version: 0.1

## Road map
#### 0.1 - Parkgate Tarn
##### Features:
1. Create development setup
2. Add details to README.md on how to create setup
3. Complete HTML CV
4. Create inital designs for Wordpress plugin

#### 0.2 - Littlewater Tarn
##### Features:
1. Work through designs to finalise look
2. Start initial HTML template work for plugin

#### 0.3 - Lanty's Tarn
##### Features:
1. Complete front-end testing on templates
2. Start work on plugin

#### 0.4 - Three Dubs Tarn
##### Features:
1. Complete work on plugin
2. Ensure unit testing is complete

#### 1.0 - Thirlmere
##### Features: 
1. HTML Version
2. Wordpress Plugin to generate CV
  1. CRUD CV 
  2. Export to JSON

#### 1.1 - Loughrigg Tarn
##### Features:
1. Expose WP-API to CV
2. Create designs for initial look of iOS app

## Change log
28/01/16 
Created inital project and wrote roadmap along side some goals

## HTML
This contains an exploration of a CV using HTML

Making it work
I use gulp to work on the buld process of development, compiling and minifying the SCSS.
<INSERT INSTRUCTIONS>

~~## Wordpress Plugin~~

## How to use
Follow the instructions on how to use gulp to build the HTML version of the cv

#### 1. Firstly you will need npm & gulp installed

To install [npm check out](https://docs.npmjs.com/getting-started/installing-node)

For gulp follow the instructions on the [main gulp repo](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md#1-install-gulp-globally)

#### 2. Install the required plugins

```sh
$ npm install gulp-ruby-sass
$ npm install gulp-livereload
$ npm install gulp-notify
```

#### 3. Install livereload in your browser

[Find out more info here](http://livereload.com/)

#### 4. Starting watching for changes

```sh
$ gulp watch
```

Each time you edit a watched file it will auto reload the page and recompile your scss if changed.