# JavaScript DOM

## What is the DOM?

The DOM (Document Object Model) is a structured representation of your web page. You can think of it as a tree of nodes, where each node can be manipulated using JavaScript.

![the DOM](../assets/images/htmltree.gif)

##### image source: [W3Schools](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.w3schools.com%2Fjs%2Fjs_htmldom.asp&psig=AOvVaw0nEHHogxLKDnkT5s8Am7Kp&ust=1678296112382000&source=images&cd=vfe&ved=0CBEQjhxqFwoTCKjS8LGqyv0CFQAAAAAdAAAAABAD)

The browser gives us the `window` object, which is the browser itself. The `window` object gives us the `document` object, which is the core of the DOM. Following that we have the `root` object which is the `html` node. The `html` node has two children, `head` and `body` that each have their on children. `head` could have children such as the page title which will have a text node as a child. The `body` node will have children such as `a` and `h1` and so on and so forth. I think you get the point.

## Manipulating the DOM

JavaScript provides us wit methods we can use to manipulate the DOM as show in the table below

| Method                   | Description                                                                                                                                                                                    |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `querySelectorAll()`     | You use this method to access one or more elements from the DOM that matches one or more CSS selectors.                                                                                        |
| `createElement()`        | Creates a specified element and inserts it into the DOM.                                                                                                                                       |
| `getElementById()`       | Get an element from the DOM using its unique id attribute.                                                                                                                                     |
| `getElementsByTagname()` | Access one or more elements in the DOM using the html tag name.                                                                                                                                |
| `appendChild()`          | It adds an element as the last child in the HTML element that calls this method. The child inserted could be newly created or moved from its previous place to the position of the last child. |
| `innerHTML`              | While this isn't a method (its a property) it still is important to know since it lets you access the text content of an element                                                               |
| `replaceChild()`         | Replace one child of an element with either a newly created element or one taken from somewhere else in the DOM.                                                                               |
| `setAttribute()`         | You can use this method to change the attribute of an element or set a value if one wasn't set initially.                                                                                      |
| `node.childNodes`        | Access all of the child nodes of a selected parent node                                                                                                                                        |
| `node.firstChild`        | Access the first child of a selected parent node.                                                                                                                                              |
| `node.lastChild`         | Access the last child of a selected parent node.                                                                                                                                               |
| `node.nextSibling`       | Access the next consecutive element of a selected element.                                                                                                                                     |
| `node.previousSibling`   | Access the previous element of a selected element.                                                                                                                                             |
