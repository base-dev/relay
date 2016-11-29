# graphql-relay-go [![Build Status](https://travis-ci.org/base-dev/relay.svg)](https://travis-ci.org/base-dev/relay) [![GoDoc](https://godoc.org/base-dev/relay?status.svg)](https://godoc.org/github.com/base-dev/relay) [![Coverage Status](https://coveralls.io/repos/base-dev/relay/badge.svg?branch=master&service=github)](https://coveralls.io/github/base-dev/relay?branch=master) [![Join the chat at https://gitter.im/base-dev/graphql](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/base-dev/graphql?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A Go/Golang library to help construct a [base-dev](https://github.com/base-dev/graphql) server supporting react-relay.

See a live demo here: http://bit.ly/try-base-dev

Source code for demo can be found at https://github.com/base-dev/playground

### Notes:
This is based on alpha version of `base-dev` and `graphql-relay-go`. 
Be sure to watch both repositories for latest changes.

### Tutorial
[Learn Golang + GraphQL + Relay Part 2: Your first Relay application]( https://wehavefaces.net/learn-golang-graphql-relay-2-a56cbcc3e341)

### Test
```bash
$ go get github.com/base-dev/relay
$ go build && go test ./...
```

### TODO:
- [x] Starwars example
- [x] HTTP handler to easily create a Relay-compliant GraphQL server _(Moved to: [base-dev-handler](https://github.com/base-dev/handler))_
- [ ] In-code documentation (godocs)
- [ ] Usage guide / user documentation
- [x] Tutorial
- [ ] End-to-end example (graphql-relay-go + react-relay)
