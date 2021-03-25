---
layout: post
title: "Routing"
permalink: /class-22
---
Jason D

##### Do child components have direct access to props/state from the parent?
* Yes, child components have access to props and state from the parent

##### When a component “wraps” another component, how does the child component’s output get rendered?
``` javascript
<Main>
  <Content />
</Main>
```
It is rendered like any html would render a child and parent relationship. The content would be nest inside the main

##### Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application?
* no

##### What trick can a parent use to share all props with it’s children
* You can use a spread operator to share all the props

### Vocabulary Terms

##### props.children
* can be used on components that represent generic boxes and don't know their children ahead of time. It can be used to display whatever you include between the opening and closing tags when invoking a component

##### composition
* the act of combining parts or elements to form a whole, components are the UI building blocks in React applications like pure functions are the building blocks of function composition.
