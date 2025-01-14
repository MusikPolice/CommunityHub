Backend services should present a RESTful API that other developers can integrate with. 

The API should be well documented and easy to understand. I've always liked the way that [HATEOAS]([HATEOAS - Wikipedia](https://en.m.wikipedia.org/wiki/HATEOAS)) creates a self-documenting API, but there may be other options.

API access will likely be authenticated with some kind of shared secret or HMAC type authentication.

Since the project is de-facto open source (see [[Licensing]]), a private or internal API that is inaccessible to external clients may not be feasible. 