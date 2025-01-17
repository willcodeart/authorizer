# Contributing

We're so excited you're interested in helping with Authorizer! We are happy to help you get started, even if you don't have any previous open-source experience :blush:

## New to Open Source?

1. Take a look at [How to Contribute to an Open Source Project on GitHub](https://egghead.io/courses/how-to-contribute-to-an-open-source-project-on-github)
2. Go through the [Authorizer Code of Conduct](https://github.com/authorizerdev/authorizer/blob/main/.github/CODE_OF_CONDUCT.md)

## Where to ask questions?

1. Check our [Github Issues](https://github.com/authorizerdev/authorizer/issues) to see if someone has already answered your question.
2. Join our community on [Discord](https://discord.gg/Zv2D5h6kkK) and feel free to ask us your questions

As you gain experience with Authorizer, please help answer other people's questions! :pray:

## What to work on?

You can get started by taking a look at our [Github issues](https://github.com/authorizerdev/authorizer/issues)  
If you find one that looks interesting and no one else is already working on it, comment on that issue and start contributing 🙂.

Please ask as many questions as you need, either directly in the issue or on [Discord](https://discord.gg/Zv2D5h6kkK). We're happy to help!:raised_hands:

### Contributions that are ALWAYS welcome

1. More tests
2. Improved Docs
3. Improved error messages
4. Educational content like blogs, videos, courses

## Development Setup

### Prerequisites

- OS: Linux or macOS or windows
- Go: (Golang)(https://golang.org/dl/) >= v1.15

### Familiarize yourself with Authorizer

1. [Architecture of Authorizer](http://docs.authorizer.dev/)
2. [GraphQL APIs](https://docs.authorizer.dev/core/graphql-api/)

### Project Setup for Authorizer core

1. Fork the [authorizer](https://github.com/authorizerdev/authorizer) repository (**Skip this step if you have access to repo**)
2. `git clone https://github.com/authorizerdev/authorizer.git`
3. `cd authorizer`
4. `cp .env.sample .env`. Check all the supported env [here](https://docs.authorizer.dev/core/env/)
5. Build the code `make clean && make`
   > Note: if you don't have [`make`](https://www.ibm.com/docs/en/aix/7.2?topic=concepts-make-command), you can `cd` into `server` dir and build using the `go build` command
6. Run binary `./build/server`
