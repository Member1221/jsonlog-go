# jsonlog-go
jsonlog-go is a logging package for doing logs compatible with inter-application communication.

jsonlog-go logs are structured as follows:
```json
{
  "unix": "(Unix timestamp)",
  "type": "(log type; info, warning, error or fatal)",
  "timestamp": "(RFC3339 timestamp)",
}
```
There's aswell an optional `data` tag that can be any type, including nil.
