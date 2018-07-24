# react-fullscreen-loading
Minimal fullscreen loading for react

## Installation

```
npm install --save react-fullscreen-loading
```

## Example

```javascript
import React from 'react';
import Loading from 'react-fullscreen-loading';

class App extends React.Component {
  render() {
    return(
      <Loading loading background="#2ecc71" loaderColor="#3498db" />
    )
  }
}

export default App;
```


## Props

Name | Type | Default Value
------------ | ------------- | -------------
loading | boolean | false
background | String  | `rgba(236, 240, 241, 0.7)`
loaderColor | String  | `#e74c3c`
