#Angular V1

[CodeSchool course on Angular V1](http://campus.codeschool.com/courses/shaping-up-with-angular-js)
[PluralSight Angular Fundamentals Course](https://app.pluralsight.com/library/courses/angularjs-fundamentals/table-of-contents)

##Background

##Getting Angular V1
*[Download angular.min.js](http://angularjs.org)
*[Download bootstap.min.css](http://getbootstrap.com)

##Including Angular V1

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" type="text/css" href="bootstrap.min.css" />
  </head>
  <body>
    <script type="text/javascript" src="angular.min.js"></script>
  </body>
</html>
```

##Minimal Example

```javascript
function StoreController(){
  alert('hello');
}
```

```html
<!DOCTYPE html>
<html>
  <body ng-controller="StoreController">
  </body>
</html>
```

##Modules
We define dependencies for our app here.
Makes app more maintainable and testable.
Use dependancy injections.

```javascript
var app = angular.module('store', [])
```

```html
<!DOCTYPE html>
<html ng-app="store">
  <head>
    <link rel="stylesheet" type="text/css" href="bootstrap.min.css" />
  </head>
  <body>
    <script type="text/javascript" src="angular.min.js"></script>
    <script type="text/javascript" src="app.js"></script>
    <p>{{"hello" + " you"}}</p>
  </body>
</html>
```

[Expressions doc](http://docs.angularjs.org/guide/expression)

##Controllers
Controllers are the beginning of everything Angular does.
A controllers primary responsibility is to create a scope object.
A controller contains logic and state Views/Directives.

##Scope
A scope object is what is used by a controller to communicate with a view thru two way communication.

##Services
Place to contain core business logic and state of project, communicate with server

##Routing

##Directives

###Built In Directives

##Testing
Karma

##Dependency Injection

##Two Way Binding



