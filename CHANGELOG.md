# Changelog — socket4h

## [1.0.0] — 2026-06-28

### Added

- Initial release
- `socket4h_connect(host, port)` — connect WiFiClient to TCP server
- `socket4h_loop()` — read incoming newline-delimited JSON, dispatch callbacks; auto-reconnect
- `socket4h_send(type, doc)` — serialize and send a JSON line
- `socket4h_on_message(type, callback)` — register handler per message type
- `socket4h_connected()` — check connection state
