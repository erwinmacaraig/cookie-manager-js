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
Retrieving a cookie with given cookie name
```js
   CookieManager.get(name);
```
- `name (String)` cookie name

### Updating a Cookie
Updating an existing cookie
```js
   CookieManager.update(name, value, expires, domain, path, secure);
```
- `name (String)` cookie name
- `value (String)` cookie value
- `expires (Optional) (Number)` cookie expiration in days
- `domain (Optional) (String)` cookie domain
- `path (Optional) (String)` cookie path
- `secure (Optional) (String)` cookie SSL support flag

### Deleting a Cookie
Deleting a cookie with given cookie name
```js
   CookieManager.remove(name);
```
- `name (String)` cookie name

### Listing All Cookies
Returns all of the existing cookies
```js
   CookieManager.getAll();
```
### Clearing All Cookies
Clears all of the existing cookies
```js
   CookieManager.clear();
```

## Author and License 
Created and maintained by [erwinmacaraig] under [MIT](License.md) License
