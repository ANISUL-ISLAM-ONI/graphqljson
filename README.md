# GRAPHQLJSON

> Graphql Json data and object

---

## Getting Started

> npm install https://github.com/ANISUL-ISLAM-ONI/graphqljson.git

````js
// typedefs.js
const { GraphQLJSON, GraphQLJSONObject } = require('graphqljson');

const typeDefs = `
scalar JSON
scalar JSONObject

type MyType {
  myValue: JSON
  myObject: JSONObject
}
# ...
# ...
`;

// resolvers.js
const resolvers = {
  JSON: GraphQLJSON,
  JSONObject: GraphQLJSONObject,
  ...
  ...
};

````