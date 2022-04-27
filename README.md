# Stripe paymwnt with Nodejs and Express Server
## Prerequisites
- JavaScript
- Nodejs
- Express
- Fetch/axios api

First you need to intall the following express, cors, dotenv, nodemon stripe

    npm install --save-dev nodemon express cors stripe
    
- Set app your first express server
- import stripe from stripe(private_key)
- If you're running your server in from different folder with your client there is need to setup cors to avoid block 
- craete your first endpoint that will create the payment session 
- head to stripe.com and create your account
- get the secret key and remember to use dotenv file so as to not deploy it to github


# Author
### Maxwel Ochieng

## License
The MIT License (MIT)

Copyright (c) 2016 Dmitri Pavlutin

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
