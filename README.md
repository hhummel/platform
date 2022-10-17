## Platform

Exploration of the current generation of technologies underpinning HealthVerity's Platform infrastructure.

The goal here isn't to use any of that proprietary technology, but rather to exercise the enabling tools:

- Github Actions
- AWS CDK
- AWS Step Functions
- AWS EventBridge

The first milestone is to build a cron application firing events on a fixed schedule, where CI/CD is managed with Github Actions and the deploy to AWS is managed using the CDK.
