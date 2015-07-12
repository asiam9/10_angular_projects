Based on [Udemy 10 Angular Courses](https://www.udemy.com/learn-angularjs-development/#/)

- Refactored to John Papa styleguide
- uses un-minified angular.js for better error messages
- uses CDN for angular-bootstrap  (bower errors)
- db.createCollection('articles');     -    db.articles.insert({ title : 'Artilce one' })   
- db.categories.update({name:'Technology'}, {$set: {description: 'learn more about tech stuff'}})

## Instagram Gallery App
- ngRoute, ngResource, bootstrapLightbox, instagram API
- [Angular Lightbox](https://github.com/compact/angular-bootstrap-lightbox)
- *node server*    (simple express)
- display popular photos, click on photo to create lightbox.  Uses angular.forEach() to scroll through

## AutoFind
- MEAN.js               (me, 4444)
- *Update ui-bootstrap* to version 0.12
- Fetch and Display cars
- CRUD for cars
- public/modules/core...
- new *cars* module   -  copy from articles, make changes
- create cars collection and insert some data in mongo shell
- add $scope.find() to core controller to populate front page with cars
- - use car.name notation on edit-car.html view

## Knowledgebase
- MEAN stack app, scaffold using Express
- ngRoute, Bootstrap  (starter html template)
- CRUD app for articles w/ categories

## JobFinder
- MEAN.js scaffold
- CRUD app for creating jobs

## Sails Auth
- User Auth App
- Sails, Foundation, Toastr
- > sails new    > sails generate api user

## PubNub Chat
- grunt serve     (grunt build, grunt test)     Scaffold  =  yo angular
- pubnub.com API for realtime requests
- Log in + Create Room + Chat
- add Presence (detects user leaves/joins channel), Storage & Playback



  (function(d, s, id){
     var js, fjs = d.getElementsByTagName(s)[0];
     if (d.getElementById(id)) {return;}
     js = d.createElement(s); js.id = id;
     js.src = "//connect.facebook.net/en_US/sdk.js";
     fjs.parentNode.insertBefore(js, fjs);
   }(document, 'script', 'facebook-jssdk'));