Movies App
==========

![](/Resources/Main.png)![](/Resources/Movie.png)![](/Resources/Artist.png)![](/Resources/Search.png)

Requirements
------------

* Node 10+
* Npm 6+
* Ionic 4+
* Ionic Lab 1+

```
$ brew install node
$ npm install -g npm@latest
$ npm install -g ionic@rc
$ npm install -g @ionic/lab@rc semver
```

Created with Ionic CLI version 4.0.0 RC:

```
$ ionic start i4demo blank --type=angular --cordova
```

Create "The Movie Database" API Key
--------------------------------------

* Go to https://themoviedb.org and create your API KEY.
* Set your key in the file `src/app/services/tmdb.service.ts`:

```
  private readonly params = {
    api_key: 'PUT_HERE_YOUR_TMDB_API_KEY',
    language: 'PUT_HERE_YOUR DESIRED_LANGUAGE' // en-US, es-ES, ...
  };
```

Preparing
---------

```
$ npm install
$ npm run fetch-plugins
```

Building
--------

```
$ ionic build
```

Running App - Serve
-------------------

```
$ ionic serve
```
