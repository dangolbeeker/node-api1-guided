[ Client ] - send a request --> [ Server (API) ]

[ Server ] - send a response -- > [ Client ]

```js
const request = {
  headers: {},

  body: {},
};

const createUser = function(url, data) {
  return axios.post(url, data); // the data goes in request.body
};
```

