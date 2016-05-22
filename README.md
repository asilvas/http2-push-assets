# HTTP/2 Push-Assets

**Internet-Draft** aiming to solve document dependency state by extending HTTP/2, bringing cutting-edge performance gains
through the worst of network conditions.

* [Latest Internet-Draft (In Progress)](https://github.com/asilvas/http2-push-assets/blob/master/draft-asilvas-http-push-assets-00.txt) ([html](https://github.com/asilvas/http2-push-assets/blob/master/draft-asilvas-http-push-assets-00.html) or [txt](https://github.com/asilvas/http2-push-assets/blob/master/draft-asilvas-http-push-assets-00.txt))


## Clients

* [http2-push-assets-node](https://github.com/asilvas/http2-push-assets-node#client) - Vanilla Node.js client
* (Potentially) [http2](https://github.com/request/request/issues/1982) - Future version of the popular Node.js request client
* (Potentially) [request](https://github.com/molnarg/node-http2) - Node.js Http2 client


## Servers

* [http2-push-assets-node](https://github.com/asilvas/http2-push-assets-node#server) - Vanilla Node.js server connect middleware



## Demos

* [http2-push-assets-demo](https://github.com/asilvas/http2-push-assets-demo) - Demo of Push-Assets Client & Server in Node.js

### Load Time by Protocol

![Load Time by Protocol](https://raw.githubusercontent.com/asilvas/http2-push-assets-demo/master/images/load-time-by-protocol.png)

### Load Time by Latency

![Load Time by Latency](https://raw.githubusercontent.com/asilvas/http2-push-assets-demo/master/images/load-time-by-latency.png)

### HTTP/1 Waterfall

![HTTP/1 Waterfall](https://raw.githubusercontent.com/asilvas/http2-push-assets-demo/master/images/load-time-http1.png)

### HTTP/2+TLS Waterfall

![HTTP/2+TLS Waterfall](https://raw.githubusercontent.com/asilvas/http2-push-assets-demo/master/images/load-time-http2+tls.png)

### HTTP/2+TLS+Push Waterfall

![HTTP/2+TLS+Push Waterfall](https://raw.githubusercontent.com/asilvas/http2-push-assets-demo/master/images/load-time-http2+tls+push.png)
