### Terminal
* `$ lsof -i:8080` Find process occupying given port
* `$ kill -9 $(lsof -t -i:8080)` Kill process occupying given port

### Visual Code Shortcuts
* `CTRL + SHIFT + P`  Terminal popup
* `CTRL + '+'`  Zoom-in
* `CTRL + '-'`  Zoom-out
* ```CTRL + SHIFT + ` ``` Terminal open

### Node.js

#### Useful Libraries
* [nodemon](https://www.npmjs.com/package/nodemon): Automatically restarts node application when changes detected in any file in directory.
* [morgan](https://www.npmjs.com/package/morgan): HTTP request logger middleware for node.js
* [body-parser](https://www.npmjs.com/package/body-parser): Parse incoming request bodies in a middleware before your handlers, available under the req.body property.
* [errorhandler](https://www.npmjs.com/package/errorhandler): Development-only error handler middleware.
* [lodash](https://lodash.com/): Javascript utility library.
* [nconf](https://www.npmjs.com/package/nconf): Hierarchical node.js configuration with files, environment variables, command-line arguments, and atomic object merging.
* [prompt](https://www.npmjs.com/package/prompt): A beautiful command-line prompt for node.js
* [Pug](https://www.npmjs.com/package/pug): high performance template engine.
* [uglify-js](https://www.npmjs.com/package/uglify-js): UglifyJS is a JavaScript parser, minifier, compressor and beautifier toolkit.

#### Important Commands
* `npm install`: Install node project dependencies.
* `nvm install [VERSION]`: Install node version.
* `nvm user [VERSION]`: Use different node version.

### Google Cloud Platform
#### gcloud
* `gcloud auth application-default login`:  Authenticate GCP services.
* `gcloud config list`: Verify default projects.
* `gcloud config set project [YOUR_PROJECT_ID]`: Set default 
project.
* `gcloud app deploy`: Deploy node application on Google app engine.

#### Google AppEngine


