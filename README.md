# React-Toastify

React-Toastify is a fork of [fkhadra/react-toastify](https://github.com/fkhadra/react-toastify) repository a little bit customized by AvaiBook team.

## Installation

```bash
npm install avaibook/react-toastify#v9.0.0
yarn add avaibook/react-toastify#v9.0.0
```

## The gist

```jsx
  import React from 'react';

  import { ToastContainer, notify } from 'react-toastify';
  import 'react-toastify/dist/ReactToastify.css';
  
  function App(){
    const displayNotification = () => notify("Wow so easy!");

    return (
      <div>
        <button onClick={displayNotification}>Notify!</button>
        <ToastContainer />
      </div>
    );
  }
```

## Demo

[A demo is worth a thousand words](https://fkhadra.github.io/react-toastify/introduction)

## Documentation

Check the [documentation](https://fkhadra.github.io/react-toastify/introduction) to get you started!

## License

Licensed under MIT
