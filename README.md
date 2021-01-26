# JavaScriptBasics
Code example for JavaScript basic level course.

## Declare a variable and assign a value to it in JavaScript
var test=10; or 
var name='John';

## Get a HTML control by Id
document.getElementById('controlId')

## Get multiple HTML controls by name
document.getElementsByName('controlName')

## Hide a HTML control - Change the style.display to none
document.getElementById('controlId').style.display = 'none';

## Show a HTML control - Change the style.display to block
document.getElementById('controlId').style.display = 'block';

## Set HTML SPAN control content - Change the inner HTML
document.getElementById('controlId').innerHTML = 'new text';

## JavaScript function to check if a value is numeric or not
isNaN(value) - returns true if value is not a numeric

## Create an object(This is one way of creating object). This represents User object which has properties like firstName, lastName etc.
var user = {
        firstName: 'John',
        lastName: 'SMith',
        Address: {
            Street: '',
            City: ''
        }
};
