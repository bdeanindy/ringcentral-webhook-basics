# RingCentral Webhook Basics Sample App

This application is built to help provide developers with a clear understanding of how to utilize RingCentral Subscriptions using Webhooks.

## Prerequisites

* RingCentral account with [Developer Portal](https://developers.ringcentral.com) access
* ngrok or a web server which supports SSL/TLS v1.2
* Node.js installed locally
* NPM installed locally
* RingCentral Soft Phone for testing inbound and outbound events

## Installation

* Clone the repository `git clone https://github.com/bdeanindy/ringcentral-webhook-basics.git`
* Install the dependencies `npm install`
* Configure environment variables
    * `mv env.tmpl .env`
    * Fill in all the values of `.env` as indicated

## Operation

* Deploy to your webserver or start ngrok
* `npm start`

You should see the subscription start, and an initial POST request for the webhooks, then you can use the RingCentral Soft Phone to make/take calls, SMS, fax, and change your status. You should see events in the log.

## License

The MIT License (MIT)
Copyright (c) <2016> <copyright RingCentral, Inc. Benjamin Dean>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
