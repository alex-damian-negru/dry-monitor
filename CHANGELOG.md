<!--- DO NOT EDIT THIS FILE - IT'S AUTOMATICALLY GENERATED VIA DEVTOOLS --->

## 0.3.2 2020-04-09


### Fixed

- Ensure `Dry::Monitor::Rack::Middleware` is compatible with `Rack::Builder#use` (@jodosha)

### Changed

- Performance improvements (@davydovanton)

[Compare v0.3.1...v0.3.2](https://github.com/dry-rb/dry-monitor/compare/v0.3.1...v0.3.2)

## 0.3.1 2019-06-18


### Fixed

- Uninitialized constant `Dry::Monitor::Notifications::EMPTY_HASH` when no payload given (@mensfeld)


[Compare v0.3.0...v0.3.1](https://github.com/dry-rb/dry-monitor/compare/v0.3.0...v0.3.1)

## 0.3.0 2019-01-29


### Fixed

- cannot load such file -- rack/utils (mensfeld)

### Changed

- Make `rack` logger into a plugin (mensfeld)
- Make `sql` logger into a plugin (mensfeld)

[Compare v0.2.0...v0.3.0](https://github.com/dry-rb/dry-monitor/compare/v0.2.0...v0.3.0)

## 0.2.0 2018-01-21


### Changed

- Make `rouge` an optional dependency (davydovanton & mensfeld)

[Compare v0.1.2...v0.2.0](https://github.com/dry-rb/dry-monitor/compare/v0.1.2...v0.2.0)

## 0.1.2 2018-01-04


### Fixed

- Rack logger no longer prevents arbitrary payload in `:error` events (solnic)


[Compare v0.1.1...v0.1.2](https://github.com/dry-rb/dry-monitor/compare/v0.1.1...v0.1.2)

## 0.1.1 2018-01-03


### Fixed

- Query params containing arrays of primitives (e.g. `?ids[]=1&ids[]=2`) no longer crash the logger (timriley)


[Compare v0.1.0...v0.1.1](https://github.com/dry-rb/dry-monitor/compare/v0.1.0...v0.1.1)

## 0.1.0 2018-01-02


### Fixed

- Query params are logged correctly via rack middleware (solnic)

### Changed

- Uses `dry-events` for notifications (solnic)

[Compare v0.0.3...v0.1.0](https://github.com/dry-rb/dry-monitor/compare/v0.0.3...v0.1.0)

## 0.0.3 2017-08-28


### Changed

- Update default theme setting for compatibility with latest version of rouge (alexandru-calinoiu)
- Require latest version of rouge gem (timriley)

[Compare v0.0.2...v0.0.3](https://github.com/dry-rb/dry-monitor/compare/v0.0.2...v0.0.3)

## 0.0.2 2017-02-02


### Added

- `Dry::Monitor::Rack::Middleware#on` shortcut (solnic)
- `Dry::Monitor::Rack::Middleware#instrument` shortcut (solnic)
- `Dry::Monitor::SQL::Logger` can be configured with a custom message template (solnic)

### Changed

- `Dry::Monitor::Rack::Logger#{subscribe=>attach}` and now it accepts a rack middleware instance (solnic)
- `Dry::Monitor::Rack::Logger` appends new lines when logging `:rack.request.stop` events (solnic)

[Compare v0.0.1...v0.0.2](https://github.com/dry-rb/dry-monitor/compare/v0.0.1...v0.0.2)

## 0.0.1 2017-02-01

First public release
