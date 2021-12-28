# 🖇️ use-merge-refs

[![npm version](https://badge.fury.io/js/use-merge-refs.svg)](https://badge.fury.io/js/use-merge-refs)

React Hook that merges two or more refs into a single one.

# Installation

```js
npm install use-merge-refs
```

# Demo

Checkout the [demo](https://codesandbox.io/s/use-merge-refs-0ng7l?file=/src/App.js) page to see useMergeRefs in action ⛹️

# Usage

```js
import useMergeRefs from 'use-merge-refs';

function Example() {
  const catRef = React.useRef();
  const dogRef = React.useRef();
  const refs = useMergeRefs(catRef, dogRef);

  return <div ref={refs} />;
}
```

# License

Copyright Wojciech Mietlinski. (MIT License)
