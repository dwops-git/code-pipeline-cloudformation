## code pipeline cloudformation

This repo is configured with Github Action that will trigger as soon as there will be a Pull Request. Githu Actions will create an AWS Code Pipeline (thas has AWS Code Build step) using Cloudformation template present in the repo (pipline-stack.yaml).

As soon as Pull Request gets merged or marked as closed then another Github Action will get triggered that will delete the cloudformation stack created earlier.
