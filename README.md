# thedom

Understanding client-side JavaScript frameworks
JavaScript frameworks are an essential part of modern front-end web development, providing developers with tried and tested tools for building scalable, interactive web applications. Many modern companies use frameworks as a standard part of their tooling, so many front-end development jobs now require framework experience. In this set of articles, we are aiming to give you a comfortable starting point to help you begin learning frameworks.

As an aspiring front-end developer, it can be hard to work out where to begin when learning frameworks — there are so many different frameworks to choose from, new ones appear all the time, they mostly work in a similar way but do some things differently, and there are some specific things to be careful about when using frameworks.

We are not aiming to exhaustively teach you everything you need to know about React/ReactDOM, or Vue, or some other specific framework; the framework teams' own docs (and other resources) do that job already. Instead, we want to back up and first answer more fundamental questions such as:

Why should I use a framework? What problems do they solve for me?
What questions should I ask when trying to choose a framework? Do I even need to use a framework?
What features do frameworks have? How do they work in general, and how do frameworks' implementations of these features differ?
How do they relate to "vanilla" JavaScript or HTML?
After that, we'll provide some tutorials covering the essentials of some of the different framework choices, to provide you with enough context and familiarity to start going into greater depth yourself. We want you to go forward and learn about frameworks in a pragmatic way that doesn't forget about web platform fundamental best practices such as accessibility.

Get started now, with "Introduction to client-side frameworks"

Prerequisites
You should really learn the basics of the core web languages first before attempting to move on to learning client-side frameworks — HTML, CSS, and especially JavaScript.

Your code will be richer and more professional as a result, and you'll be able to troubleshoot problems with more confidence if you understand the fundamental web platform features that the frameworks are building on top of.

javascript and css frameworks and how to learn them
JavaScript frameworks were created to make this kind of work a lot easier — they exist to provide a better developer experience. They don't bring brand-new powers to JavaScript; they give you easier access to JavaScript's powers so you can build for today's web.

If you want to see code samples from this section in action, you can check out a working version of the app on CodePen, which also allows users to add and delete new tasks.
What frameworks are out there?
There are many frameworks out there, but currently the "big four" are considered to be the following.

Ember
Ember was initially released in December 2011 as a continuation of work that started in the SproutCore project. It is an older framework that has less users than more modern alternatives such as React and Vue, but it still enjoys a fair amount of popularity due to its stability, community support, and some clever coding principles.

Start learning Ember

Angular
Angular is an open-source web application framework led by the Angular Team at Google and by a community of individuals and corporations. It is a complete rewrite from the same team that built AngularJS. Angular was officially released on the 14th of September 2016.

Angular is a component-based framework which uses declarative HTML templates. At build time, transparently to developers, the framework's compiler translates the templates to optimized JavaScript instructions. Angular uses TypeScript, a superset of JavaScript that we'll look at in a little more detail in the next chapter.

Start learning Angular

Vue
After working on and learning from the original AngularJS project, Evan You released Vue in 2014. Vue is the youngest of the big four, but has enjoyed a recent uptick in popularity.

Vue, like AngularJS, extends HTML with some of its own code. Apart from that, it mainly relies on modern, standard JavaScript.

Start learning Vue

React
Facebook released React in 2013. By this point, it had already been using React to solve many of its problems internally. Technically, React itself is not a framework; it's a library for rendering UI components. React is used in combination with other libraries to make applications — React and React Native enable developers to make mobile applications; React and ReactDOM enable them to make web applications, etc.

Because React and ReactDOM are so often used together, React is colloquially understood as a JavaScript framework. As you read through this module, we will be working with that colloquial understanding.

React extends JavaScript with HTML-like syntax, known as JSX.

Start learning React
Read more about the JavaScript used in this section:

<a href="https://developer.mozilla.org/en-US/docs/Web/API/Document/createElement">document.createElement()</a>
<a href="">document.createTextNode()</a>
<a href="">document.createDocumentFragment()</a>
<a href="">eventTarget.addEventListener()</a>
<a href="">node.appendChild()</a>
<a href="">node.removeChild()</a>

