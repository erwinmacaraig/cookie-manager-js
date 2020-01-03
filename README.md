# cookie-manager-js 
Lightweight, simple and easy cookie management library in Javascript

[![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg)]() [![PyPI](https://img.shields.io/pypi/status/Django.svg)]() 

This is a library for providing more useful and powerful interface to manage cookies.
- No Dependency
- Supports AMD, CommonJS, Node modules
- Lightweight 1KB
- Supported by all browsers

## Installation
Download the `cookie-manager.min.js` and include in your project.

```html
<script src="cookie-manager.min.js"></script>
```

## Usage
After include the `cookie-manager.min.js` you will be able to use `CookieManager` object. 

You can also `CookieManager` object as an AMD, CommonJS or Node module 


## Functionalities

### Creating a Cookie
Creating a new cookie
```js
   CookieManager.set(name, value, expires, domain, path, secure);
```
- `name (String)` cookie name
- `value (String)` cookie value
- `expires (Optional) (Number)` cookie expiration in days
- `domain (Optional) (String)` cookie domain
- `path (Optional) (String)` cookie path
- `secure (Optional) (String)` cookie SSL support flag


### Retrieving a Cookie

### Updating a Cookie

### Deleting a Cookie

### Listing All Cookies

### Clearing All Cookies
