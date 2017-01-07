[![Spriv Logo](http://spriv.com/wp-content/uploads/2015/03/logo25.png)](http://spriv.com)

# node-spriv
- **Unofficial** NodeJS [SDK](http://spriv.com/api-code-two-factor-authentication-workflow/) for [Spriv](http://www.spriv.com)
- The worlds most advanced, secure and affordable 2FA on the market.

# Node Spriv
The Official NodeJS SDK of Spriv 2FA

# Prerequisites

1. Create account on spriv.com
2. Create an API Access Key

## Quick Start

  Create the app:

```bash
$ mkdir newApp
$ cd newApp
$ npm init
```

  Install node-spriv as a dependency:

```
$ npm install --save node-spriv
```

Example Use

```js
// index.js
var app_key = ""        //Your Spriv App Key
var app_secretkey = ""  //Your Spriv App Secret Key
var spriv = require("node-spriv")(app_key, app_secretkey)


// Now you are ready to begin using spriv

```
