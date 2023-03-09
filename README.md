# Server-Sent-Event basic template

## Client side hitting:

```
let sse = new EventSource("http://localhost:8080/stream")
sse.onmessage = console.log
```
