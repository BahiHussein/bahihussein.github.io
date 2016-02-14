---
layout: post
title: Understanding AngularJS scope.$watch
---
$scope.$watch in angular is for listening for scope changes; for-example, if you have a contact form and want to show instance error message for the user when he/she enters invalid format, you will need to listen for the changes made on the form to check for the validity of the changes.

## How it works?
one way of using scopes that you ask the scope to watch a specific scope variables for changes, when changes are made the scope should execute a given function.  So, you need to provide you $scope.$watch method with two arguments, the scope variable that you want to watch and the function that will be executed on changes.


```
function MainController($scope) {
   
   $scope.myVar = "";

   $scope.$watch('myVar', function() {
       alert('myVar has changed!');
   });

}
```


In the above snippet, i have passed the scope variable name and a function to the $scope.$watch method. The function will be executed on the scope variable changes showing an alert message.

## Watching an Object
What do i mean by watching objects? if you have a form object and this form object has name and email fields. You may not want to watch the changes on each of them separately, but check changes on the form object which includes both the name and the email. In other words, you will check the changes on both using at the same method.

```
function MainController($scope) {
   
   $scope.form = {};
   $scope.form.name = "";
   $scope.form.email = "";

   //instead of watching form.name separately
   $scope.$watch('form.name', function() {
       alert('name has changed!');
   });

   //instead of watching form.email separately
   $scope.$watch('form.email', function() {
       alert('email has changed!');
   });

  //you can simply watch the form object and it will listen for the both (name and email)

}
```

Listening for object changes is little different from watching variable changes. The scope.$watch method compares the oldValue of the the watched variable to the newValue and check if any changes were made, but when comparing two complex objects the scope.$watch method checks if the oldValue and the newValue have the same reference, which is properly not what you want. For the scope.$watch method to compare objects values instead of reference you will need  to pass “true” as a third arguments.

```
function MainController($scope) {
   
   $scope.form = {};
   $scope.form.name = "";
   $scope.form.email = "";

   //watching the 'form' object
   $scope.$watch('form', function() {
       alert('form fields has changed!');
   },true);
```

