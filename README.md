# MongoDB w/ Native Queries - May 2024 Community Call Demo

This demo provides a practical example of building an Ecommerce App using Hasura's Data Delivery Network (DDN) with a [supergraph](https://supergraph.io) architecture.

## Instructions

- [Import data from data folder into your mongodb](https://www.mongodb.com/docs/compass/current/import-export/)
- [Install Hasura CLI](https://hasura.io/docs/3.0/cli/installation)
- [Login to Hasura CLI](https://hasura.io/docs/3.0/cli/commands/login)
- [Create Project](https://hasura.io/docs/3.0/cli/commands/create-project)
- Copy Project Name. Feel free to delete the project folders/files that were created. Cloning the repo will regenerate all of that for you. All you need is the project name.
- Git Clone [Repo](https://github.com/hasura/mongo-communitycall-demo.git) and cd into it
- Go to hasura.yaml and replace "change-me" with the one you get in the step above.
- Go to base.env.yaml and replace "change-me" with your mongodb connection string

- run [ddn build supergraph-manifest](https://hasura.io/docs/3.0/cli/commands/build-supergraph-manifest) -d "Description of Build"
  - For more details on the build process, refer to the [Build Process](#build-process) section.
- go to console and explore
