# [React](https://reactjs.org/) · ![license MIT](1.svg) ![npm v17.0.2](2.svg) ![circleci passing](3.svg) ![PRs welcome](4.svg)
React is a javascript library for buidling user interfaces
  * **Declarative:** React makes it painless to creat interactive UIs.Design simple views for each state in your application,and React will efficently update and render just the right components when your data changes.Declarative views make your code more predictable,simpler to understand,and easier to debug.
  * **Compoent-Based:** Build encapsulated components that manage their own state, then compose them to make complex UIs. Since componet logic is written in JavaScript instead of templates,you can easily pass rich data through your app and keep state out of the DOM.
  * **Learn Once, Write Anywhere:** We don't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code. React can also render on the server using Node and power mobile apps using [React Native](https://reactnative.dev/).

Learn how to use React in your own project.

## Installation
React has been designed for gradual adoption from the start, and you can use as little or as much React as you need:
  * Use [Online Playgrounds](https://reactjs.org/docs/getting-started.html#online-playgrounds) to get a taste of React.
  * [Add React to a Website](https://reactjs.org/docs/add-react-to-a-website.html) as a `<script>` tag in one minute.
  * [Create a New React App](https://reactjs.org/docs/create-a-new-react-app.html) if you're looking for a powerful JavaScript toolchain.

You can use React as a `<script>`, tag from a [CDN](https://reactjs.org/docs/cdn-links.html), or as a `react` package on[npm](https://www.npmjs.com/package/react).

## Documentaion

You can find the React documentaion [on the website](https://reactjs.org/).

Check out the [Getting Started](https://reactjs.org/docs/getting-started.html) page for a quick overview.

The doucumentation is divided into several sections:

  * [Tutorial](https://reactjs.org/tutorial/tutorial.html)
  * [Main Concepts](https://reactjs.org/docs/hello-world.html)
  * [Advanced Guides](https://reactjs.org/docs/jsx-in-depth.html)
  * [API Reference](https://reactjs.org/docs/react-api.html)
  * [Where to Get Support](https://reactjs.org/community/support.html)
  * [Contributing Guide](https://reactjs.org/docs/how-to-contribute.html)

You can impove it by sending pull requests to [this repoistory](https://github.com/reactjs/reactjs.org)

## Examples

We have several examples [on the website](https://reactjs.org/). Here is the first one to get you started:

  function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}

  ReactDOM.render(
  <HelloMessage name="Taylor" />,
  document.getElementById('container')
);

This example will render "Hello Taylor" into a container on the page.

You'll notice that we used an HTML-like syntax;[we call it JSX](https://reactjs.org/docs/introducing-jsx.html).JSX is not required to use React, but it makes code more readable, and writing it feels like eriting HTML.If you're using React as a `<scriptd>` tag, read [this section](https://reactjs.org/docs/add-react-to-a-website.html#optional-try-react-with-jsx) on integrating JSX; otherwise, the [recommended JavaScript toolchains]
(https://reactjs.org/docs/create-a-new-react-app.html) handle it automatically.

## Contributing

The main purpose of this repository is to continue evolving React core, making it faster and easier to use. Development of React happens in the open on Github, and we are grateful to the communtiy for contributing bugfixes and improvements. Read below to learn how you can take part in improving React.

## Code of Conduct

Facebook has adopted a Code of Conduct that we expect project participants tp adher to. Please read [the full text]()

## Contributing Guide

Read our contributing guide to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to React.

## Good First Issues

TO help you get your feet wet and get you familiar with our contribution process, we have a list of good first issues that contain bugs which have a realatively limited scope. This is a great place to get started.
## License

React is MIT licesed.
