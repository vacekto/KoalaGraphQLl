Koala GraphQL assignment

# About
Simple Graphql Typescript API. To be honest, this task took me longer then I would like. While I was familiar with basic contepts, for example that GraphQL lets users fetch selected data in a single request, I bashed (pun intended) my head on all sorts of problems, from setting up the environment, through remebering SQL queries, to figuring out the most suitable approach to project structure, simply because I had never tried to build GraphQL api up until now. 
The whole task took me about 20 to 25 hours and leaves much to be desired. Like any proper API, there should be some sort of test coverage, altough writing tests is not my favourite pastime, env variables are hardcoded in DOCKERFILE, CI/CD pipeline would be nice, not to mention that project currently isnt deployed anywhere and runs only locally.

# Dev stack
- Docker
- Typescript
- Graphql-http
- express
- codegen (for generating types from .graphql schema files)
- pg (PostgreSQL client)


# Takeaway
Main takeaway is not to get sidetracked. Instructions specificelly mentioned not to strive for perfection, but simply get the job done to a point of working version in as little time as possible. This is generally my weakness, one on which I will work in the future.

# to run
(linux, bash and Docker required, scripts will likely also require to add execute permissions)
- clone repo
- run ./bin/build.sh
- run ./bin/run.sh
