# Porter demo fixture

This repository publishes the inert, same-origin pages used to verify Porter's
single-approved-link research path during OpenAI Build Week.

- [`/research/start/`](https://godlydonuts.github.io/porter-demo-fixture/research/start/)
  contains one ordinary link labeled `Read the static details`.
- That link resolves directly to `/research/details/` on the same origin.
- The terminal details page contains static evidence and no further navigation.
- Neither page contains JavaScript, forms, authentication, tracking, redirects,
  external resources, or download behavior.

The source fixture is versioned as `porter-research-v1`. Its passive-page
contract is checked in the main Porter repository before deployment. This site
does not contain the Porter application, credentials, model output, or user
data.
