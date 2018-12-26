![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Lab 29

### Author: Ashley Breunich

### Links and Resources
* [repo](https://github.com/ashley-breunich/lab-29)
* [Assignment 1](https://codesandbox.io/s/6l7qro54mk)
* [Assignment 2](http://xyz.com)

### Modules

## Assingment 1

#### `app.js`
##### Exported Values and Methods

###### `Class App -> <div>`
The App Class renders and returns a div that passes the state down to its child, Stuff.

###### `Stuff(props) -> <Things />`
The Stuff function receives the state from its parent (App) and then passes the state down another level to its child, Things. 

###### `Things(props) -> <span>`
The Things function receives the state from its parent (Stuff) and then returns the props in a single span.

### Setup
#### `.env` requirements
* `NODE_PATH` - NODE_PATH=src

#### Tests
For the Assignment 1, I tested that the div that was supposed to render, rendered. I also tested that the state I expected to exist, existed. 

#### UML
Link to an image of the UML for your application and response to events
