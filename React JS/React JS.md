# React JS

React is one of the most well-liked JavaScript frameworks for developing single-page applications. Being a JavaScript framework, it should go without saying that you should be familiar with JavaScript ideas.

## Roadmap for learning React

### 1. What to learn before React <br>
### 2. What to learn as a beginner to React <br>
### 3. How to move from beginner to intermediate React developer <br>
### 4. How to move from intermediate to advanced React developer <br>

<hr>

## What to learn before learning React.
 As `React` is javascript based. To speed up your React learning at full speed, you'll need to be familiar with a few things in addition to some fundamental JavaScript knowledge.

 * Git Version Control 

    * `Git` is a version control programme that aids in better managing your source code. There is no direct connection between it and ReactJS. However, learning its fundamental applications will help you make the most of the development ecosystem.

    * Git is easy when you concentrate on a few fundamental principles, such as,
        * How to initiate a repository
        * How to stage/unstage your changes
        * How to commit your changes to the repo
        * How to push to the remote repository
        * How to resolve merge conflicts?

    * You'll need to understand how to use Git as well as a Git-based repository management service like GitHub.

    * You can learn about `git` and `github` in this [video](https://www.youtube.com/watch?v=apGV9Kg7ics&t=2111s) by Kunal Kushwaha.

 * HTML (Hyper Text Markup Language)

    * A web page's structure is provided by HTML. When you code in ReactJS, you will utilise a new syntax called JSX, which uses the HTML structure.

    * HTML is not something you have to be an expert in. However, you should have a fundamental understanding of the most popular tags and semantics. You can see this [crash course](https://www.freecodecamp.org/news/html-crash-course/) on HTML.

* CSS (Cascading Style Sheets)

    * When it comes to CSS, the scope is sky-high. However, focus on the topics like:
        * Basic Selectors
        * Pseudo-Classes and how to combine
        * Box model
        * Flexbox
        * Grid
        * Postioning (Relative, Absolute...)
        * Basic units like em, rem, px...

    * Visit this [site](https://css-tricks.com/) to learn about CSS.

* JavaScript

    * You must know the following concepts from JavaScript,
        * Variable Declarations (let and const)
        * Template Literals
        * Functions & Arrow Functions
        * Object Destructuring
        * Spread and Rest Operators
        * Module Import and Export
        * A bit of Promises and Async Programming

    * You can do this free [course](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/) of JavaScript.

* NPM Ecosystem

    * To run and test a ReactJs project locally, you should know how to use `npm`, `yarn`, and node version manager (nvm).

    * You can watch this [video](https://www.scaler.com/topics/javascript/install-node-js/), on how to install these.

    * It's usually helpful to understand how they operate at a high level so you can debug your environment if a problem arises.

## What to learn as a beginner to React?

* Do you understand what React is?

    * You should understand what is so special about ReactJs. It is a declarative, component-based user interface library.
    * You can see what this means [here](https://reactjs.org/).
* Find out how to configure your development environment.
    * There are multiple ways to set up a development environment for ReactJs. Minimally, you can point to the CDN distribution from your script file.

    * This approach is okay to get started but not sustainable. As a beginner, you may not want to spend too much time in Babel or Webpack related configurations for your projects.

    * IMO, the most intelligent and quickest way to get started with the ReactJS development environment is by using the Create React App. You can follow the easy steps on its homepage to get it running in a few minutes.

* JSX

    * ReactJS allows the user interface logic to couple with rendering logic, events, handling state changes, and more. This coupling is to encourage the practices of building self-contained components.

    * JSX is a syntax that looks like HTML but also has the power of JavaScript. This syntax helps developers write UI logic with all necessary elements like data fetching, conditions, looping, expressions, etc.

    * Note that you can write a ReactJS app without using JSX syntax – but the development experience will not be as good.

    * Here's a great resource to help you learn about [JSX in React](https://www.freecodecamp.org/news/jsx-in-react-introduction/).

* React Components

    * Components are the heart of ReactJs applications. We create independent components that are reusable, self-contained, and isolated. A component is supposed to perform one job correctly. Multiple components come together to build the application.

    * In ReactJS, you can create components using JavaScript classes or simple functions. I advocate using functional components as it is more straightforward and require lesser coding.

    * An article on how to [write better components](https://www.freecodecamp.org/news/how-to-write-better-react-components/).

    * and an article on [intro to react components](https://www.freecodecamp.org/news/how-to-write-better-react-components/).

* State in React

    * State is your component's own data. States are not shared between components. Your component's "state," which you utilise to render and alter information

    * You can check out this [in-depth guide](https://www.freecodecamp.org/news/what-is-state-in-react-explained-with-examples/) to state in React to get a better understanding of how it works.

* Props in React

    * You will require the components to communicate with one another in order to programme in the actual world. The data must be passed between components even when states are private to a component. Props have a role in this situation. Props are read-only; take note of this.

    * Here's a quick tutorial on [props in react](https://www.freecodecamp.org/news/how-to-use-props-in-react/).

* List and Keys in React

    * We use list to render a list of items in a React component. It is a very common task to list users, TODO items, and other things. We use the map() function to iterate over the list and render the results.

    * Keys help identify what item from the list has changed to inform React to re-render. ReactJS gives a warning if you forget to mention the keys for a list.

## How to Move from Beginner to Intermediate React Developer

* Styling

    * We all want our applications to look fresh and aesthetically pleasing. You can use plain old CSS to style your ReactJS app. Or you can use Sass or other CSS-driven component libraries like `TailwindCSS`, `ChakraUI`, `react-bootstrap`, or `MUI`. The choice is entirely yours.

* Form Handling

    * Handling forms is an essential requirement in web applications. You need to understand how to handle form elements in the ReactJS way.

    * For example, you can use the react-hook-form library to build forms easily. Here are a couple tutorials to [get you started](https://www.freecodecamp.org/news/how-to-build-react-forms/) with [react-hook-form](https://www.freecodecamp.org/news/build-forms-in-react-with-react-hook-form-library/).

* Data Handling

    * This is a crucial part of application development. You need to learn how to use the `fetch API` or libraries like `node-fetch` and `axios` to interact with APIs and handle data in your component.

* Reconciliation Process

    * ReactJS uses the Virtual DOM and diffing algorithm to decide when and what to update in the actual DOM for the rendering. Knowing how it works under the hood will help you with debugging.

    * Here's a good starter guide [on the DOM](https://www.freecodecamp.org/news/dom-explained-everything-you-need-to-know-about-the-document-object-model/), or Document Object Model, and here's one on how to [manipulate the DOM](https://www.freecodecamp.org/news/how-to-manipulate-the-dom-beginners-guide/). Then you can check out this overview of the [Virtual DOM](https://www.freecodecamp.org/news/a-quick-guide-to-learn-react-and-how-its-virtual-dom-works-c869d788cd44/) and how it works in React.

## How to move from intermediate to advanced React developer

* Lazy Loading in React

    * ReactJS supports code splitting. It is a way to lazy load what you need by the current user. It also avoids producing a large build bundle. The `dynamic import` feature is the best way to include code-splitting in a React app.

    * Here's a basic tutorial on [lazy loading in React](https://www.freecodecamp.org/news/how-to-use-react-lazy-and-suspense-for-components-lazy-loading-8d420ecac58/) to get you started.

* Portals in React

    * You may have to use Portals when dealing with modals, dialogs, or tooltips with better event handling. It is supported out-of-the-box in ReactJS.

* State Management in React

    * In a larger application, you must share information between components. At times, the default support of `Props` and `Context` may not suffice.

    * In these cases, you may need a state management solution like `Redux` or `MobX` in these cases. But again, you can decide whether (or not) you'll need them.

* Routing

    * Routing is required for multi-page applications. It is also helpful to bookmark a particular page or traverse back-and-forth in the application using the browser's back button.
    
    * [React Router](https://reactrouter.com/) is the most popular routing solution that helps with declarative routing.

    * Here's an in-depth [guide](https://www.freecodecamp.org/news/learn-react-router/) to learning React Router that'll get you started with all the basics.

* Themeing

    * Theming is a modern feature in web apps. We should give users the choice of what theme they want – like light or dark – to use to help them feel comfortable when using your site or app.

    * You can even [create your custom](https://theme-builder.netlify.app/) themes in some applications and apply them. There are several ways you can theme a React app. Select the one that matches the best with your application's CSS stack.

* Patterns in React

    * There are various patterns you can use as solutions to common problems in React. Over time, ReactJS developers have found patterns they could use to help them stop reinventing the wheel.

    * Learning these patterns will help you considerably. Check out this [site](https://reactpatterns.com/) to find the most used ReactJS Patterns documented with examples.

* Anti-Patterns in React

    * Anti-Patterns are the practices that you should avoid using in the ReactJS applications. You should learn them along with the helpful patterns you should use.


Just keep in mind that learning advanced React concepts doesn't stop here. You can continue to learn about accessibility, test frameworks, and many more advanced concepts as needed.

I hope you found the roadmap helpful. Please plan to get enough practice as you start walking through the path. 