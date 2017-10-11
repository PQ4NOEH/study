# Introduction
+ [Course code](https://github.com/StephenGrider/GraphQLCasts)
+ Restful routing:
  - Verbs
    + create = POST.
    + Get = fetch.
    + Put = Update overall resource.
    + Patch = Update a specific part of the resource.
    + DELETE = delete the resource.
  + routing
    - /[resource-name]
    - /[resource-name]/:id
    - /[resource-name]/:id/[resource-name]
    - /[resource-name]/:id/[resource-name]/:id (weird!!) ![alt text](https://d30y9cdsu7xlg0.cloudfront.net/png/99960-200.png)

## Why it exists?
Walk a resource graph in a restful manner might be very challenging when the graph becomes nested. Options:
+ Parent request one request for each received child. The drawbacks are
  - Too many HTTP requests
  - Too clumsy code
+ Nesting routing (/users/23/friends/companies || /users/23/friends/positions). drawbacks
  - Not very generic, becomes more specific and less close to the standard as a consequence the API becomes more difficult to understand
+ Create specific endpoint users/23/friends_with_companies_and_positions. drawbacks
  - We break restful conventions.
  - They are very specific and that makes them less reusable.

In conclusion, graphql amends to solve two big issues when working with rest-full routing and highly relational data:
1. Routing complexity and out of standard.
2. Too many HTTP requests.
3. Over-fetching data.
## What is it?
A data manipulation and quering language
## How do we use it?
+ Queries
