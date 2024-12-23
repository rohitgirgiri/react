# React Developer Roadmap (2024) ⚛️

A thorough React developer roadmap for 2024 that addresses all aspects of React and beyond.

<details>

<summary>0. Before you start React</summary>

You should know and be comfortable with **all of the following:**

-   [**Basic HTML**](https://www.w3schools.com/html/default.asp)

    -   HTML Elements, Attributes, Headings, Paragraphs, Colors & Styles
    -   HTML Links, Images, Tables, Lists, Block & Inline, Div, Classes, Id
    -   HTML Forms
    -   HTML Layout, Responsiveness & Semantic

-   [**Basic CSS**](https://www.w3schools.com/css/default.asp)

    -   CSS Basics - Syntax, Selectors, Colors, Backgrounds, Borders, Margin, Padding, Height/Width, Box Model, Outline, Text, Fonts, Links etc.
    -   CSS More - Lists, Tables, Display, Position, z-index, Overflow, Float, Inline Block, Align, Combinators, Pseudo-classes & elements, Opacity etc.
    -   CSS Forms & Layouts
    -   CSS Flexbox
    -   CSS Grid
    -   Advanced CSS - CSS Units, Shadows, Gradients, Transitions, Animations, Specificity etc.

-   [**Basic Tailwind CSS**]

    -   Tailwind Utilities
    -   Responsive Variants
    -   Hover, focus and other states
    -   Dark Mode variant
    -   Tailwind Directives
    -   Tailwind Configurations
    -   Theme Configurations
    -   [Tailwind cn() utility]

-   **Document Object Model (DOM)**

    -   [DOM Basics - Basics, Method, Document, Elements, Forms, CSS, Events, Navigation, Nodes and Collections]
    -   [DOM Advanced]

-   [**Basic JavaScript**]

    -   JS Basics - Statements, Expressions, Syntax, Variables, Operators, Data Types, Functions, Objects, Arrays, Events, Array and String Methods, Object Methods, Date, Conditionals, Error Handling, JavaScript OOP - classes and inheritance and Debugging
    -   JS Web APIs - Forms, History, Geolocation, Storage, Worker and Fetch API
    -   JS JSON

-   [**JavaScript Advanced**]

    -   Solid JS Concepts - Scope, Hosting, Execution Context, Closures, Prototype, Recursion, Primitive vs Reference Data Types, Currying, Intersection Observer, Memoization, Event Propagation, Debounce etc.
    -   [Asynchronous JavaScript]- Callbacks, Promises and async-await

-   [**Modern JavaScript**]

    -   Different ES6+ JS Syntaxes and concepts eg. Arrow function, Truthy/Falsy values, Ternary Operator, Different Array methods like find, filter, map, reduce, slice, splice, push, pop, concat, different looping strategies, Spread & Rest Operator, Array and Object Destructuring, Imports/Exports syntax, Template Literals, Sorting etc.

-   [**Git/GitHub**]

    -   [Basics of Git]
    -   [Important Git Commands]

</details>

<details>
<summary>1. React Fundamentals</summary>

You should know and be comfortable with **all of the following:**

-   **Getting Started with React**
    -   Introduction to React - Why React - Comparison with Vanilla JS
    -   React Installation & Editor Setup with Vite
    -   How React works - Virtual DOM
    -   Basics of React Components
    -   Basics of JSX: React's Markup
    -   JavaScript in JSX
    -   Passing Props to Components
    -   Conditional Rendering
    -   Rendering Lists
    -   Pure Components
    -   How to split larger components into smaller ones
-   **Adding Interactivity**

    -   Responding to Events - Event Handlers
    -   Understanding States - React Component's Memory - useState
    -   How State works in React
    -   How Rendering works in React
    -   Updating complex states immutably in React

-   **React State Management Deep Dive**

    -   Declarative vs Imperative UI
    -   Thinking UI Declaratively
    -   Finding & Structuring React States
    -   Connecting Event Handlers to React
    -   Sharing State between components
    -   Lifting State up
    -   Extracting State Logic into Reducers
    -   useReducer Hook
    -   How to use Immer with React for concised immutable State Update
    -   Passing Data Deeply inside React Components
    -   Avoiding Prop Drilling - Context API & useContext Hook
    -   Combine context and reducer to write scalable code

</details>

<details>
<summary>2. Advanced React</summary>

-   Referencing values with Refs - useRef hook
-   Manipulating the DOM with Refs
-   Synchronizing with Effects - useEffect hook
-   Separating events from Effects
-   Removing Effect Dependencies
-   Performance optimization with useCallback and useMemo hook
-   Reusing logic with Custom Hooks
-   Calling APIs from Back-end with React

</details>

<details>
<summary>3. Advanced State Management</summary>

-   [Using Redux / Toolkit]
-   [Using Zustand]
-   [Using Jotai]
-   [Using Recoil]
-   [Using MobX]

</details>

<details>
<summary>4. Styling Solutions</summary>

-   [**Tailwind**](https://tailwindcss.com/)
-   [**CSS Modules**](https://www.makeuseof.com/react-components-css-modules-style/)
-   [**Styled Components**](https://styled-components.com/)
-   React UI Component Library - [Shadcn](https://ui.shadcn.com/)
-   [React UI Component Library - Keep React]
-   [**Material UI**](https://mui.com/)
-   [**Chakra UI**](https://chakra-ui.com/)
-   [**Ant Design**](https://ant.design/docs/react/introduce)

</details>

<details>
<summary>5. React Ecosystem & Use Cases</summary>

-   [React Router DOM]
-   API Request with Axios in React
-   React Suspense & Error Boundaries
-   React Lazy Load
-   React Infinite Scroll
-   Uncommon React Hooks - useDebugValue, useDeferredValue, useId, useImperativeHandle, useInsertionEffect, useLayoutEffect and useTransition
-   **React Authentication**

    -   How to handle user sign in (email, password, JWT)
    -   How to handle access tokens and token refreshes
    -   Social sign in (Google, Facebook, GitHub, etc.)
    -   [Using Supabase](https://supabase.com/)
    -   [Using Firebase](https://firebase.google.com/docs/auth)
    -   [Using Clerk](https://clerk.com/)

-   **Form Handling in React**

    -   How to validate user input in forms (emails, passwords, etc.)
    -   How to send form data to the server
    -   How to handle file uploads
    -   [Using React Hook Form](https://react-hook-form.com/)
    -   [Using Formik](https://formik.org/docs/overview)

-   [**Accessibility**](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/React_accessibility)
    -   Understanding why accessibility is important
    -   [Using semantic HTML](https://www.semrush.com/blog/semantic-html5-guide/)
    -   How to implement keyboard navigation
    -   How to add aria labels
    -   [Using React Aria](https://react-spectrum.adobe.com/react-aria/)
-   **Testing**
    -   [How to implement unit tests](https://www.freecodecamp.org/news/how-to-write-unit-tests-in-react/)
        -   [Using React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
        -   [Using Jest](https://jestjs.io/)
    -   [How to implement e2e integration tests]
        -   [Using Cypress](https://www.cypress.io/)
        -   [Using Playwright](https://playwright.dev/)

</details>

<details>
<summary>6. React Frameworks</summary>

You should have worked with **one of the following:**

-   [**Vite**](https://vitejs.dev/)
    -   How to run a simple React application
-   [**Next.js**](https://nextjs.org/)
    -   [Understanding file-based routing](https://nextjs.org/docs/app/building-your-application/routing)
    -   [Understanding Next Auth](https://next-auth.js.org/)
    -   [Understanding server components](https://nextjs.org/docs/app/building-your-application/rendering/server-components)
    -   [Understanding server actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations)
-   [**Remix**](https://remix.run/)

</details>

<details>
<summary>7. Beyond React</summary>

-   **Team player**
    -   How to work within a team
    -   How to perform code reviews
    -   How to give and receive feedback
-   **Efficiency**
    -   How to prioritize tasks
    -   How to handle tech debt
    -   How to meet deadlines and goals
-   **Continuous Learning**
    -   How to continuously learn and grow
    -   How to stay up to date with your skills
-   **Networking & Communication** - Going to meetups or events - Contributing to open source projects - Networking within the company you work in
</details>

## Resources to learn React.js

> Some free and paid resources that might help you achieve your goal of becoming a React Developer

[React Official Documentation](https://reactjs.org/docs/gettingtarted.html): The official documentation is a comprehensive guide to understanding and using React.

[Learn React by Scrimba](https://scrimba.com/learn/learnreact): Learn React by Scrimba

[Full Modern React Tutorial by Net Ninja] Full Modern React Tutorial by Net Ninja


[React.js on MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/React_getting_started): MDN Web Docs provides a step-by-step guide to getting started with React.js.

[freeCodeCamp - React.js Full Course]: A full course on React.js by freeCodeCamp available on YouTube.

[Scotch.io - Getting Started with React](https://scotch.io/starters/react/getting-started-with-react): A beginner-friendly tutorial on React on Scotch.io.

[React.js Documentation on GitHub](https://github.com/facebook/react): Explore the React.js source code and contribute to the project on GitHub.

[React Patterns](https://reactpatterns.com/): Discover common design patterns in React.js development.

[React DevTools](https://reactjs.org/blog/2019/08/15/new-react-devtools.html): Learn about the React DevTools for debugging React applications.

[React Armory](https://reactarmory.com/): A collection of free resources, guides, and courses to learn React.


[Fullstackopen - Introduction to React](https://fullstackopen.com/en/part1/introduction_to_react): A free online course covering the basics of React.js by the University of Helsinki.

[Egghead.io - React Fundamentals](https://egghead.io/courses/react-fundamentals): Egghead.io offers free lessons on React fundamentals.

[React - The Complete Guide 2024 (incl. React Router & Redux)](https://www.udemy.com/course/react-the-complete-guide-incl-redux/?ranMID=39197&ranEAID=jU79Zysihs4&ranSiteID=jU79Zysihs4-bggwPPY8PbL9EU0xYBWUlA&LSNPUBID=jU79Zysihs4&utm_source=aff-campaign&utm_medium=udemyads): React - The Complete Guide 2024 (incl. React Router & Redux)

[Complete React Developer in 2023 (w/ Redux, Hooks, GraphQL)](https://zerotomastery.io/courses/learn-react/): Complete React Developer in 2023 (w/ Redux, Hooks, GraphQL) by ZTM.

[React 18 for Beginners](https://codewithmosh.com/p/ultimate-react-part1): React 18 for Beginners by Code With Mosh.

[React Basics](https://www.coursera.org/learn/react-basics): React Basics by Meta.

[Advanced React](https://scrimba.com/learn/react): Advanced React by Scrimba.



