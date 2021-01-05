[![Netlify Status](https://api.netlify.com/api/v1/badges/1e34f043-cac5-4b1d-907e-7b9ead642624/deploy-status)](https://app.netlify.com/sites/react-github-stats-card-demo/deploys)
# Demo Application for `react-github-stats-card` for React v.16 and React-DOM v.16

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Usage

```js
// src/App.js
import React from 'react';
import './App.css';
// import Card from package
import Card from 'react-github-stats-card/dist/Card';

function App() {
  return <Card username="cnocon" theme={true} />
}

export default App;
```