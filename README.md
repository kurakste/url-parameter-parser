# Simple and lightweight url decoder.
  Just help extract key-value from GET URL string.
  Result will be object key-value.

## Installation

$ npm install url-parameter-parser

## Getting started

```
const parser = require('url-parameter-parser');

const testString = '/socket.io/?uid=3&EIO=3&transport=polling&t=Mq-166I';

const res = parser(testString);

returns: 
  {
    uid: 3,
    EIO: 3,
    transport: 'polling',
    t:'Mq-166I',
  }
```