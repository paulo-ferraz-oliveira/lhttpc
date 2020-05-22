# lhttpc

[![](https://travis-ci.com/MiniclipPortugal/lhttpc.png?branch=master)](https://travis-ci.com/MiniclipPortugal/lhttpc)

`lhttpc` is a **lightweight** HTTP client.

## Usage

```erlang
URL = "https://www.google.com",
Method = get,
Hdrs = [],
Timeout = 5000, % in milliseconds

lhttpc:request(URL, Method, Hdrs, Timeout).
```
