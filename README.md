# jonh-package 📦

## 🎯 Install 



### CDN
```javascript
 <script src="https://unpkg.com/john-package@1.0.3/index.js"></script>

```

### npm

```bash
npm i -s john-package
```

## 🧬 Usage 
After install the package;

Import the package and use it like the example below 👇

Go to your console of your browser and check the message

```javascript

import React from 'react';
import logo from './logo.svg';
import './App.css';
import x from 'john-package';


x.greetings();

function App() {

  return (
   
    <div className="App">
     
      <header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <p>
          Edit <code>src/App.js</code> and save to reload.
        </p>
        <a
          className="App-link"
          href="https://reactjs.org"
          target="_blank"
          rel="noopener noreferrer"
        >
          Learn React
        </a>
      </header>
    </div>
  );
}

export default App;

```


### Or

```javascript
...

const john = require('john-package');


john.greetings();
   
 ...  
````


## License

### Made By [João Gomes](https://joaosilgo.github.io/joaogomes/)

#### 
