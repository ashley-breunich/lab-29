![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Lab 29

### Author: Ashley Breunich

### Links and Resources
* [repo](https://github.com/ashley-breunich/lab-29)
* [Assignment 1](https://codesandbox.io/s/6l7qro54mk)
* [Assignment 2](https://codesandbox.io/s/rvy8vq7np)


### Modules

## Assignment 1

#### `app.js`
##### Exported Values and Methods

###### `Class App -> <div>`
The App Class renders and returns a div that passes the state down to its child, Stuff.

###### `Stuff(props) -> <Things />`
The Stuff function receives the state from its parent (App) and then passes the state down another level to its child, Things. 

###### `Things(props) -> <span>`
The Things function receives the state from its parent (Stuff) and then returns the props in a single span.

#### `index.js`
##### Exported Values and Methods

###### `Class Main -> <App />`
The Main Class renders and returns the App component

## Assignment 2

#### `app.js`
##### Exported Values and Methods

###### `Class App -> <div>`
The App Class renders and returns a div that passes the state down to its child, Stuff.

#### `stuff.js`
##### Exported Values and Methods

###### `Stuff Functional Component`
The Stuff component receives the state from its parent (App) and then passes the state down another level to its child, Things. 

#### `things.js`
##### Exported Values and Methods

###### `Things Functional Component`
The Things component receives the state from its parent (Stuff) and then returns the props in a single span.


### Setup
#### `.env` requirements
* `NODE_PATH` - NODE_PATH=src


#### Tests
For Assignment 1, I tested that the div that was supposed to render, rendered. I also tested that the state I expected to exist, existed. 


For Assignment 2, the tests were fairly similar except I separated test files out for each component and I tested that what was returned was accurate. 


I wasn't able to figure out how to test if a component returned another component but I know there must be a way to do that. Also, I am curious if there is a way to test for what props are being passed down to the child elements. 


#### UML
[UML Link](assets/UML-lab29.jpg)