# movieApp
Manage favorite movie listing..
Creating a CRUD App in Minutes with Angular’s $resource

Most Single Page Applications involve CRUD operations. If you are building CRUD operations
using AngularJS, then you can leverage the power of the $resource service. Built on the top
of the $http service, Angular’s $resource is a factory that lets you interact with RESTful
backends easily. So, let’s explore $resource and use it to implement CRUD operations in
Angular.
Prerequisites
The $resource service doesn’t come bundled with the main Angular script. You need to
download a separate file called angular-resource.js and include it in your HTML page. The
script can be downloaded from http://cdnjs.cloudflare.com/ajax/libs/angular.js/1.2.16/angularresource.min.js.
Also, your main app module should declare a dependency on the ngResource module in order
to use $resource . The following example demonstrates how to do it:

ref: http://www.sitepoint.com/creating-crud-app-minutes-angulars-resource/
