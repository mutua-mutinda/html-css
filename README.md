### ONLINE SHOP

⋅⋅⋅A simple website that allows a client order a product online.⋅⋅⋅

#### GET STARTED

⋅⋅⋅To create this website you need to have ``Nodejs`` as the programming language in your machine to use and ```Expressjs``` framework.⋅⋅⋅

How to install Expressjs 
    ``` npm install --save expressjs```

### VIEW ENGINE
⋅⋅⋅EJS Templating was used for development and to generate HTML markup with javascript.⋅⋅⋅

 #### INSTALLATION
 ``` $ npm install --save ejs```


### MIDDLEWARES USED
1. Body-parser
    install the the body-parser middlware through npm.
    ``` $ npm install --save body-parser```

    #### API
    ```var bodyParser = require('body-parser')``

2. Express session
    session are used to give a log
    ```$ npm install -- save express-session```

    #### API
    ```var session = require('express-session')```

3. Cookie-parser    
    This middleware takes a secret, parses cookies attached to the client request object. 
        ```$ npm install --save cookie-parser``

    ### API
    ```var express = require('express')
        var cookieParser = require('cookie-parser')
        
        var app = express()
        app.use(cookieParser())
    ```

### FEATURES
- [x] Uploads Products to the online shop.
- [x] Client successfully adds the product to a cart ready for checkout.
- [x] 

