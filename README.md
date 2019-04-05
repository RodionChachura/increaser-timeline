# increaser-timeline

> 

[![NPM](https://img.shields.io/npm/v/increaser-timeline.svg)](https://www.npmjs.com/package/increaser-timeline) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

![alt text](https://cdn-images-1.medium.com/max/2000/1*x82VVUaS-xuLv-BzjTn_wQ.gif)

## [Demo](https://rodionchachura.github.io/increaser-timeline/)

## Install

```bash
npm install --save increaser-timeline
```

## Usage

```jsx
import React from 'react'

import Timeline from 'increaser-timeline'

const Container = ({ children }) => (
  <div style={{ height: '100vh' width: '100%' }}>
    {children}
  </div>
)

class Example extends React.Component {
  constructor(props) {
    super(props)
    this.state = { sets: [] }
  }

  render() {
    const { sets } = this.state
    return (
      <Timeline
        wrapper={Container}
        sets={sets}
      />
    )
  }
}
```
## [Story on Medium](https://medium.com/p/124bdfe727db)

## License

MIT © [RodionChachura](https://geekrodion.com)