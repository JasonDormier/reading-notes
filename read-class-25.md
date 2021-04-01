---
layout: post
title: "Hooks Api"
permalink: /class-24
---
Jason D

##### What does a component’s lifecycle refer to?
 A series of methods that are invoked in different stages of the component’s existence.
* Inititalization
* Mounting
* Updating
* Unmount((ing

##### Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect()
* In order to keep things tidy and wrap up any process that is using resources that it shouldn't once the useEffect() has compeleted

##### Why are functional components preferred over class components?
* They are easier to use when you get the hang of them, cleaner and easier to read. They are also less lines of code

##### What is wrong with the following code?
* The only thing I can think of is pushing the div into an array


```javascript
import React, {useState, useEffect} from 'react';

function MyComponent(props) {
  const [count, setCount] = useState(0);

  function changeCount(e) {
    setCount(e.target.value);
  }

  let renderedItems = []

  for (let i = 0; i < count; i++) {
    useEffect( () => {
      console.log('component mount/update');
    }, [count]);

    renderedItems.push(<div key={i}>Item</div>);
  }

  return (
      <div>
     <input type='number' value={count} onChange={changeCount}/>
      {renderedItems}
    </div>
    );
}
```
### Vocabulary Terms

##### state hook
* useState() which operates simalar to this.setState() in class.

##### effect hook
* useEffect() which reaplaces componentDidMount, componentDidUpdate, and componentWillUnmount

##### reducer hook
* An alternative to useState. Accepts a reducer of type (state, action) => newState, and returns the current state paired with a dispatch method. (If you’re familiar with Redux, you already know how this works.)
