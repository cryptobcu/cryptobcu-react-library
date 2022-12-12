# cryptobcu-react-library

> Colorfull Neon Buttons


[![NPM](https://img.shields.io/npm/v/cryptobcu-react-library.svg)](https://www.npmjs.com/package/cryptobcu-react-library) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save cryptobcu-react-library
```

## Usage

```jsx
import React, { Component } from 'react'

import { NeonButton as MyComponent } from 'neon-button-ui'
import 'neon-button-ui/dist/index.css'

class Example extends Component {
  render() {
    return (
      <MyComponent
        type='pink'
        text='Click Me'
        onClick={() => alert("Hello, I'm neon Button...")}
      />
      <MyComponent
        type='blue'
        text='Click Me'
        onClick={() => alert("Hello, I'm neon Button...")}
      />
      <MyComponent
        type='purple'
        text='Click Me'
        onClick={() => alert("Hello, I'm neon Button...")}
      />
      <MyComponent
        type='orange'
        text='Click Me'
        onClick={() => alert("Hello, I'm neon Button...")}
      />
      <MyComponent
        type='yellow'
        text='Click Me'
        onClick={() => alert("Hello, I'm neon Button...")}
      />
      <MyComponent
        type='green-dark'
        text='Click Me'
        onClick={() => alert("Hello, I'm neon Button...")}
      />
      <MyComponent
        type='green-light'
        text='Click Me'
        onClick={() => alert("Hello, I'm neon Button...")}
      />
      <MyComponent
        type='cyan'
        text='Click Me'
        onClick={() => alert("Hello, I'm neon Button...")}
      />
      <MyComponent
        type='black'
        text='Click Me'
        onClick={() => alert("Hello, I'm neon Button...")}
      />
      <MyComponent
        type='red'
        text='Click Me'
        onClick={() => alert("Hello, I'm neon Button...")}
      />
    )
  }
}
```
<img src="./dist/neon-button-gif.gif" align="center" widht="800px" height="600px">

## License

MIT © [cryptobcu](https://github.com/cryptobcu)
