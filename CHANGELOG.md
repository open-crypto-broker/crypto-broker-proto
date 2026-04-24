# Changelog

The list of commits in this changelog is automatically generated in the release process.
The commits follow the Conventional Commit specification.

## [0.2.0] - 2026-04-24

### 🚀 Features

- Add workflow lint (#14)
- Use hash tagged actions, fix lint issues (#13)
- Included correlation id into optional trace context (#11)
- Created definition of fake endpoint to test gRPC built-in support for retries (#9)
- Switched to explicit tracing fields (#8)

### 🐛 Bug Fixes

- Adjust workflow permissions (#16)
- Refactor workflow lint action (#15)
- Tracing context is optional (#10)

### 🚜 Refactor

- Adjust certificate validity fields (#7)

### ⚙️ Miscellaneous Tasks

- Update actions to latest version for Node 24 support (#12)

## [0.1.0] - 2025-12-02

### 🚀 Features

- Add Markdownlint and release changelog workflows (#6)
- Add benchmark messages and adjust service name (#4)
- Add gRPC health include (#2)
- Code Migration (#1)

### 🚜 Refactor

- Vendor health.proto in third_party folder and remove include (#3)

### 📚 Documentation

- Adjust README with benchmark protobuf definitions (#5)
