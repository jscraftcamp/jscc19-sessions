# Microfrontends (architecture pattern)

## Where did it come from?

1. **LEGACY codebases of big organizations/projects**
2. **Translating the idea of microservices to the frontend** 

### Key points:

- Isolation is key - self-contained parts (micro apps) will be combined by a thin "shell" application to a "seamless" SPA or MPA
- Independent releases solve many problems
- Independent teams maintaining a microservice/micro-UI-app combo for their domain independently
- support legacy while solving tech debt and innovating with new code

**BAD:** 

- PERFORMANCE (angular1 AND React AND backboneJS - all with their vendor bundle)
- shared state is hard
- shared routing is complicated

**GOOD:**

- **Independent deployments**
- Independent teams
- Independent releases

## For new projects created from scratch:

- get the PROs from above list without the issues?!
- solve problems with sensible conventions (performance
- share state with e.g. Apollo-GraphQL
- isolate but not too much: webcomponents
- hybrid routing
    - shell page routing,
    - micro app subrouting
