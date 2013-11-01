# Caliper Ember 

### Bower Library

This repository is meant to be used with [bower](http://bower.io)
You should have bower installed already if you want to use this package.
These files are also available through the Caliper application dashboard.

### Getting Started

    $ bower install caliper-ember

### Including Caliper in your App

Caliper extends Ember.js to collect performance data as your users interact with
your application. This must be loaded after Ember has been loaded, but before
any of your application's code are loaded.

### Configuring your API Key

Include the following Javascript snippet to configure Caliper

    var Caliper = {
      config: { apiKey: "77e3433c-4a89-4e38-b8e2-f5d2df53abfc" }
    };
