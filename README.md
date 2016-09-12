# noop

> Just a no-operation function.

## Install

```bash
npm install noop --save 
```

## Usage

```js
import React, { Component, PropTypes } from 'react';
import noop from 'noop';

class Child extends Component {
  static propTypes = {
    onClick: PropTypes.func
  };

  static defaultProps = {
    onClick: noop
  };
}
```

---
