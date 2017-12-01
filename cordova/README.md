# Angular + Cordova application schema

## install

```sh
$ cp -R thisDir /global/node/modules/@angular/cli/node_modules/@mytemplate 
```

I want to `npm install -g` this template, but I can not do it yet.

## create application

```sh
$ ng new myApp --collection @mytemplate/cordova --app-id com.example.app   // You can use other `ng new` options.
$ cd myApp
$ npm run restore
```


This template does not include platforms and plugins. Please add as necessary.

