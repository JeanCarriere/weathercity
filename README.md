
## Question
Modify the web page so that a user will be able to enter a city name.
Giving this name, the application will display its current weather.
The app will consume the openweather REST api to get this result (http://openweathermap.org/api).


## Building / running

### Pre requisites:
Install npm, grunt, bower, sass and compass.

### Preparing

Run `npm install` once to install the components described in `package.json`, required to run `grunt`.

Run `bower install` to download your web app dependencies described in bower.json to `app/bower_components`.

### Running

Note: You need to have your backend server running.

To run the app:

`grunt serve`

It will:

 - run a server to serve your web app static assets on port 9000, with a reverse proxy to your backend server on port
  8000, a file watching mechanism to rebuild your sass assets, and live reload support so that your browser is
  refreshed whenever you make changes to your sources

