# React Cookie Manager
React Cookie Manager is a lightweight NPM library that simplifies managing cookies in React applications. With this library, you can easily set, get, and remove cookies using a simple and intuitive API, without worrying about the underlying implementation details.

## Installation
You can install React Cookie Manager using NPM:

```shell
npm install react-cookie-manager
```

```shell
yarn add react-cookie-manager
```

## Usage
To use React Cookie Manager in your React application, simply import the `setCookie` `getCookie`, and `removeCookie` functions from the `react-cookie-manager` module, like so:

```javascript

import { setCookie, getCookie, removeCookie } from 'react-cookie-manager';

// Set a cookie with the name 'myCookie' and the value 'myValue', with an expiry of 7 days
setCookie('myCookie', 'myValue', { expires: 7 });

// Get the value of the cookie with the name 'myCookie'
const myValue = getCookie('myCookie');

// Remove the cookie with the name 'myCookie'
removeCookie('myCookie');

```

The `setCookie` and `removeCookie` functions accept optional configuration options that can be used to customize the cookie's behavior. You can find more information about these options in the `js-cookie` library documentation.


## License
React Cookie Manager is licensed under the MIT License. See the LICENSE file for more information.

## Contributions
If you would like to contribute to React Cookie Manager, please open an issue or pull request on the GitHub repository. All contributions are welcome and greatly appreciated!

## Acknowledgements
React Cookie Manager is built on top of the js-cookie library, which provides a simple and lightweight API for handling cookies in JavaScript. Special thanks to the developers of js-cookie for creating such a great library!






