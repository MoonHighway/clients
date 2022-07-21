<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/GraphQL_Logo.svg/512px-GraphQL_Logo.svg.png" width="100" alt="graphql logo"/>
<img src="https://i.imgur.com/migo24P.png" width="100" alt="moon highway logo"/>
</p>

# GraphQL Clients Workshop

Welcome! We're really glad you're here! Below you'll find all of the resources that we'll use throughout this course. If you're looking for slides, samples, links, etc., this is the place to look.

## Instructor Info

- **Eve Porcello**: [Twitter](https://twitter.com/eveporcello) | [Email](mailto:eve@moonhighway.com)
- **Alex Banks**: [Twitter](https://twitter.com/moontahoe) | [Email](mailto:alex@moonhighway.com)
- **Moon Highway Training**: [Moon Highway Website](https://www.moonhighway.com) | [Mailing List](http://bit.ly/moonhighway) | [Articles](https://www.moonhighway.com/articles)

## Server Examples

- [Simple Strava Sample](https://github.com/eveporcello/simple-strava-sample/blob/master/index.js)
- [Pet Library](https://github.com/graphqlworkshop/pet-library)
- [Data Sources Docs](https://www.apollographql.com/docs/apollo-server/data/data-sources/)
- [Resolver Best Practices - PayPal Blog](https://medium.com/paypal-engineering/graphql-resolvers-best-practices-cd36fdbcef55)
- [Mutation Pet Library](https://github.com/MoonHighway/pet-library/blob/initial-version/src/resolvers/Mutation.js)

#### Simple Requests

- curl Request

```sh
curl -X POST \
     -H "Content-Type: application/json" \
     --data '{ "query": "{allLifts{name}}" }' \
     http://snowtooth.moonhighway.com
```

- [Fetch Sample](https://codesandbox.io/s/n3jro0o4n0)
- [graphql-request](https://codesandbox.io/s/4qzq5z2vz0)

### Apollo & React

- [Snowtooth UI Start Files](https://github.com/graphqlworkshop/snowtooth-ui)
- [Snowtooth UI Finished Files](https://github.com/graphqlworkshop/snowtooth-ui/tree/complete)

### Caching & Tooling

- [Caching, Client Side Schema](https://github.com/eveporcello/pet-library-client)
- [Apollo Tooling, Codegen Deprecated](https://github.com/apollographql/apollo-tooling)
- [GraphQL Code Generator](https://www.graphql-code-generator.com)


### Tutorials and Resources

- [Apollo Odyssey](https://odyssey.apollographql.com/)
- [How to GraphQL](https://howtographql.com)
- [GraphQL.org](https://graphql.org)
