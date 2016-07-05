# corsproxy

> standalone CORS proxy

[![Build Status](https://travis-ci.org/gr2m/CORS-Proxy.svg?branch=master)](https://travis-ci.org/gr2m/CORS-Proxy)
[![Dependency Status](https://david-dm.org/gr2m/CORS-Proxy.svg)](https://david-dm.org/gr2m/CORS-Proxy)
[![devDependency Status](https://david-dm.org/gr2m/CORS-Proxy/dev-status.svg)](https://david-dm.org/gr2m/CORS-Proxy#info=devDependencies)

[![NPM](https://nodei.co/npm/corsproxy.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/corsproxy/)


## Setup

```
npm install -g git://github.com/sergiu-paraschiv/CORS-Proxy
CORSPROXY_PROXY_HOST=foo.com corsproxy
# with custom port: CORSPROXY_PORT=1234 corsproxy
# with custom host: CORSPROXY_HOST=localhost corsproxy
# with debug server: DEBUG=1 corsproxy
```

## Usage

The cors proxy will start at http://localhost:1337.
The proxied domain name has to be specified with the CORSPROXY_PROXY_HOST environment variable.

Then you can use it like this:
- http://localhost:1337/sign_in
- http://localhost:1337/path/to/resource
- etc etc

## License

MIT
