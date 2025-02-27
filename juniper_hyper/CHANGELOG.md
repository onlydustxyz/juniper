# master

- Compatibility with the latest `juniper`.

# [[0.7.3] 2022-02-02](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-v0.7.3)

- Compatibility with the latest `juniper`.

# [[0.7.2] 2022-01-26](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-v0.7.2)

- Compatibility with the latest `juniper`.

# [[0.7.1] 2021-06-07](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-0.7.1)

- Compatibility with the latest `juniper`.

# [[0.7.0] 2021-04-03](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-0.7.0)

- **[Breaking change]** Remove unneccesary `Result`s ([#889](https://github.com/graphql-rust/juniper/pull/889))

# [[0.6.3] 2021-01-27](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-0.6.3)

- Compatibility with the latest `juniper`.

# [[0.6.2] 2021-01-15](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-0.6.2)

- Compatibility with the latest `juniper`.

# [[0.6.1] 2020-12-12](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-0.6.1)

- Compatibility with the latest `juniper`.

# [[0.6.0] 2020-12-09](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-0.6.0)

- Compatibility with the latest `juniper`.

## Breaking Changes

- `juniper_hyper::graphiql` now requires a second parameter for subscriptions.
- `juniper_hyper::graphql` now executes the schema asynchronously. For blocking synchronous execution consider `juniper_hyper::graphql_sync` for use.
- `400 Bad Request` is now returned if POST HTTP request contains no or invalid `Content-Type` header.

# [[0.5.2] 2019-12-16](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-0.5.2)

- Compatibility with the latest `juniper`.

# [[0.5.1] 2019-10-24](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-0.5.1)

- Compatibility with the latest `juniper`.

# [[0.5.0] 2019-09-29](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-0.5.0)

- Compatibility with the latest `juniper`.

# [[0.4.1] 2019-07-29](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-0.4.1)

- Compatibility with the latest `juniper`.

# [[0.4.0] 2019-07-19](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-0.4.0)

- Compatibility with the latest `juniper`.

# [[0.3.0] 2019-05-16](https://github.com/graphql-rust/juniper/releases/tag/juniper_hyper-0.3.0)

- Compatibility with the latest `juniper`.

# 0.2.0 [2018-12-18]

## Breaking changes

- The tokio threadpool managed by `hyper` is now used for
  executing GraphQL operations as well. Previously a separate threadpool from `futures_cpupool` was required.

  [#256](https://github.com/graphql-rust/juniper/pull/256)
