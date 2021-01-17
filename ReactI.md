## Hello everyone .. Today we will learn something beautiful and new in our course 401 :fire: :fire: .. Please have fun :blush: :sunglasses: :heart_eyes:

# Overview
ECMAScript 2015, also known as ES6, introduced many changes to JavaScript. Here is an overview of some of the most common features and syntactical differences, with comparisons to ES5 where applicable.

Here is a key of most identifier names used throughout this reference.

   * Variable: x
   * Object: obj
   * Array: arr
   * Function: func
   * Parameter, method: a, b, c
   * String: str

# Hello Word 
The smallest React example looks like this:

ReactDOM.render(
  <h1>Hello, world!</h1>,
  document.getElementById('root')
);

It displays a heading saying “Hello, world!” on the page.

Try it on CodePen

Click the link above to open an online editor. Feel free to make some changes, and see how they affect the output. Most pages in this guide will have editable examples like this one.

# Rendering an Element into the DOM

Let’s say there is a <div> somewhere in your HTML file:

<div id="root"></div>

We call this a “root” DOM node because everything inside it will be managed by React DOM.

Applications built with just React usually have a single root DOM node. If you are integrating React into an existing app, you may have as many isolated root DOM nodes as you like.

To render a React element into a root DOM node, pass both to ReactDOM.render():

const element = <h1>Hello, world</h1>;
ReactDOM.render(element, document.getElementById('root'));

Try it on CodePen

It displays “Hello, world” on the page.

# Updating the Rendered Element

React elements are immutable. Once you create an element, you can’t change its children or attributes. An element is like a single frame in a movie: it represents the UI at a certain point in time.

With our knowledge so far, the only way to update the UI is to create a new element, and pass it to ReactDOM.render().

Consider this ticking clock example:

function tick() {
  const element = (
    <div>
      <h1>Hello, world!</h1>
      <h2>It is {new Date().toLocaleTimeString()}.</h2>
    </div>
  );
  ReactDOM.render(element, document.getElementById('root'));}

setInterval(tick, 1000);

