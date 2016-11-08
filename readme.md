NPM Frontend boilerplate
=========

A frontend project template that uses **NPM scripts** for bundling. Includes **browserify** with **babelify**, **node-sass**, **autoprefixer** and **uglify-js** for bundling and *flexboxgrid*, *normalize.css* and *jQuery* imported.

## Usage

- First, clone the repo

		git clone https://github.com/vbifonixor/npm-frontend-boilerplate.git MyProject

- Open project folder and remove .git folder

		cd MyProject

		rm -rf .git

- Install dependencies

		npm install # Also builds files in the first place

- Run a development server

		npm run watch # Launches browser-sync and bundles every piece of project on file changes

### A command list you might need:

	npm run build:all # Builds scss, js and images
	npm run build:css # Builds css
	npm run build:js # Builds js

	npm run watch:css # Watches CSS, no browser-sync
	npm run watch:js # Same for JS
	npm run watch:all # Watches both CSS and JS

Some other useful commands can be found in package.json
