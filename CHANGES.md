# Changes

## 0.8 (??-??-202?)

- Added dependabot to GitHub repository [e56ca23711ac0344cbb51a3ff4f93f23c8d42a5f](https://github.com/kinow/protobuf-uml-diagram/commit/e56ca23711ac0344cbb51a3ff4f93f23c8d42a5f)

## 0.7 (06-10-2020)

- Fix TypeError: main() got an unexpected keyword argument 'fullname'
[#13](https://github.com/kinow/protobuf-uml-diagram/issues/13)

## 0.6 (24-07-2020)

- Release to include `sdist` distribution archive in PYPI

## 0.5 (27-05-2020)

- Support homonyms, by using protobuf full name of each entity
[#10](https://github.com/kinow/protobuf-uml-diagram/issues/10)

## 0.4 (03-03-2020)

- More shellcheck fixes in Docker commands
- Added support to aggregations, showing when a field is "repeated"
- Updated example image and test (happy path)

## 0.3 (17-10-2019)

- Added test coverage report
- Added more tests, and graphviz to CI pipeline
- Fixed shellcheck issues in Docker commands
- Add builder option and validation for file format (default to PNG)
- Added support for nested messages (issue #1)

## 0.2 (30-09-2019)

- Added Dockerfile (thanks to Chris Fesler)
- Better support to Protobuf FieldDescriptor types
- Add comments to code
- Implemented a builder for parameters
- Updated setup.py to include metadata for PYPI
- Added more tests

## 0.1 (22-05-2019)

- Initial prototype code, not released to PYPI, used as script in a [project](https://cylc.github.io/)
