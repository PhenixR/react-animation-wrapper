# react-animation-wrapper

A declarative set of react components wrapper to add animation, like animate.css

## Why Another Animate.css

Compared to animate.css, react-animation-wrapper has many uncomparable advantages:

1. No global css variable polution (css in js).
1. More configurable and controllable via JavaScript and React.
1. Less file size, just import the animation you need.

## Usage

```sh
npm i --save react-animation-wrapper
```

Write a custom, normal react component:

```js
const Header = () => <h1 style={{ textAlign: 'center' }}>Hello World</h1>
```

Wrap it up with the animation wrapper you like:

```js
import { BounceIn } from 'react-animation-wrapper'
ReactDOM.render(
  <BounceIn>
    <Header />
  </BounceIn>,
  document.querySelector('.root')
)
```

You are all set!

## Contribution

This project is in a sense very beginner-friendly project for those who want to get some fun of open source. It's well modularized, and the logic of each components is quite easy and similar to each other.

See the issues with the `good first issue` tag and I welcome all kinds of support and can provide some guide.
