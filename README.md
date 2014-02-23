# flynn-controller

This is the Flynn Controller. It is loosely based on the [Heroku Platform
API](https://devcenter.heroku.com/articles/platform-api-reference) and enables
management of applications running on Flynn via an HTTP API.

Currently the only consumer of the API is
[flynn-cli](https://github.com/flynn/flynn-cli).

flynn-controller communicates with the [host
service](https://github.com/flynn/flynn-host) to get the current state and run
jobs.
