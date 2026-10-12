# Changelog

## 1.0.1

### Added

- Two warnings at startup for settings that break every proxied login in a way that looks like a
  PaperGuard problem: `online-mode=true` in `server.properties`, and Velocity's own forwarding
  (`proxies.velocity.enabled` in `config/paper-global.yml`) switched on. Neither stops the plugin,
  they only say what to change.
