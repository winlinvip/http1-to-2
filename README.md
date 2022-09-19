# http1-to-2

Covert HTTP1 to HTTP2 request.

## Usage

Run this tool:

```bash
go get github.com/winlinvip/http1-to-2
~/go/bin/http1-to-2 -listen :4317 -backend ap-guangzhou.apm.tencentcs.com:4317
```

Please use [srs-apm-http1](https://github.com/winlinvip/srs-apm-http1) to write APM data to `localhost:4317` over HTTP1.

