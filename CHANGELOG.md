# Changelog

The list of commits in this changelog is automatically generated in the release process.
The commits follow the Conventional Commit specification.

## [0.5.0] - 2026-08-26

### 🚀 Features

- Adjust nonce strategy for encryptData and decryptData (#33)
- Define gRPC message size limits (#32)
- Add self-describing format and deprecation message (#31)

### 🐛 Bug Fixes

- Make EncryptMetadata and DecryptMetadata non optional (#34)

### ⚙️ Miscellaneous Tasks

- Adjust descriptor level for EncryptDataResponse (#36)

## [0.4.0] - 2026-07-24

### 🚀 Features

- Add encrypt decrypt gRPC messages (#29)
- [**breaking**] Changed hash procedure message (#25)
- [**breaking**] Removed created_at from metadata and updated docs (#22)
- Add dependabot config (#17)

### 🐛 Bug Fixes

- Limit create-github-app-token permissions (#24)
- Extract FakeEndpoint and Benchmark endpoints to separate service (#18)

### 💼 Other

- Change sign procedure contract (#26)

### 🚜 Refactor

- Change hash and sign protobuf definitions (#28)
- Adjust workflow files (#20)

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
