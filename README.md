# nooop

> Just a no-operation function.

## Install

```bash
npm install nooop --save 
```

## Usage

```js
import React, { Component, PropTypes } from 'react';
import noop from 'nooop';

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
