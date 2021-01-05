[![Netlify Status](https://api.netlify.com/api/v1/badges/1e34f043-cac5-4b1d-907e-7b9ead642624/deploy-status)](https://app.netlify.com/sites/react-github-stats-card-demo/deploys)

# [react-github-stats-card](https://github.com/cnocon/react-github-stats-card) Demo App

_for React v.16 and React-DOM v.16_

Live Demo URL: https://react-github-stats-card-demo.netlify.app/

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Usage

```js
// src/App.js
import React from 'react';
import './App.css';
// import Card from package 
import Card from 'react-github-stats-card/dist/Card';

// pass username to Card component, and optionally an accessToken (String) and theme (Boolean)
function App() {
  return <Card username="cnocon" theme={true} />
}

export default App;
```
