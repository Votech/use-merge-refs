# <img src="https://cdn-icons.flaticon.com/png/512/5288/premium/5288474.png?token=exp=1640722847~hmac=a9cc867f5698f4ade2f4f792ff8291ae" alt="MarineGEO circle logo" style="height: 50px; width:50px;" /> use-merge-refs

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

  return <div ref={refs}>Div with two refs</div>;
}
```

# License

Copyright Wojciech Mietlinski. (MIT License)

# Attributions

<div>Readme title icon made by <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>
