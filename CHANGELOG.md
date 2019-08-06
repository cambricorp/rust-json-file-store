## v0.6.0

- create temporary files within the same directory like the target file
- switched to Rust edition 2018
- use uuid v0.7.x

## v0.5.0

- use uuid v0.6.x
- add method `path()` to access storage location
- generify constructors path argument

## v0.4.0

- use serde v1.x
- use uuid v0.5.x

## v0.3.0

- BREAKING changes:
  - renamed `get_all()` to `all()`
  - dropped `rustc_serialize` support
- use serde v0.9.x

## v0.2.2

- derive `Clone` for `Store`

## v0.2.1

- new: support serde v0.7.x

## v0.2.0

- new: lock files during write
- fix: don't return an error if a directory already exists

## v0.1.1

- make configuration fields (`pretty`, `indent`, `single`) public

## v0.1.0

- Initial release
