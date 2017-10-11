# Introduction
+ [Course code](https://github.com/StephenGrider/GraphQLCasts)
+ Rest-ful routing:
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
Walk a resource graph in a rest-ful manner might be very challenging when the graph becames nested. Options:
+ Parent request one request for each received child. The drawbacks are
  - Too many http requests
  - Too clumsy code
+ Nesting routing (/users/23/friends/companies || /users/23/friends/positions). drawbacks
  - Not very generic it becomes very specific and so becomes away from standard meaning our API becomes more difficult to understand
+ Create specific endpoint users/23/friends_with_companies_and_positions. drawbacks
  - We break rest-full conventions.
  - The are very specific and that makes them less reusable.
## What it is?
## How do we use it?
