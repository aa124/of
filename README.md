of
==

this._curl('POST', headers, apiPath, params, body, statusCb, dataCb, errCb, context);  },  26 + put: function(headers, apiPath, params, body, statusCb, dataCb, errCb, context) {  this._curl('PUT', headers, apiPath, params, body, statusCb, dataCb, errCb, context); 28 + },  get: function(headers, apiPath, params, statusCb, dataCb, errCb, context) {  this._curl('GET', headers, apiPath, params, null, statusCb, dataCb, errCb, context)  },