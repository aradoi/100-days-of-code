# 100 Days Of Code - Log

### Day 1: February 1, 2021

**Today's Progress:** I forked the [Unicorn Project] (https://github.com/aradoi/unicorn) and took the time to create my dev environment - cleaned old python2.7, updated pip, npm and cdk. 

**Thoughts:** Happy about onboarding this challenge. I'm sure there is a lot to discover along the way.

**Links:**

1. [My Forked project on GitHub](https://github.com/aradoi/unicorn.git)
2. [Official website for the project](https://www.matscloud.com/docs/unicorn-project/workshop/)

### Day 2: February 2, 2021

**Today's Progress:** I continued with learning CDK code structure and CLI commands, for the purpose of interacting with AWS resources (via CF) through a high level programming language (I chose Python). I did update the environment with last pip, python and cdk. I created a dedicated AWS IAM user principle for cdk.

**Thoughts:** We're moving away from low-level representations of cloud resources as there were first represented in their native language, in favor of more abstract ones (e.g. Python vs. CF). The balance must be kept between simplicity and granularity.

**Links:**

1. [CDK workshop](https://cdkworkshop.com/)

### Day 3: February 3, 2021

**Today's Progress:** I started developing in CDK and get familiar with CDK Constructs. Coded a couple of lambda functions and an API GW to proxy all requests for the backend lambdas. Got more familiar with the code structure and how functions are called from external files.

**Thoughts:** It's important to get familiar with the concepts first and then build on top.

**Links:**

1. [CDK workshop](https://cdkworkshop.com/)

### Day 4: February 4, 2021

**Today's Progress:** I completed the CDK workshop. Today I gave lambda permissions to write to a DynamoDB table and be able to invoke dowstream lambdas. Exposed a hit counter to the internet via a pip module which was made for demo purposes, as it exposes to the internet without authentication the whole content of the table. Looked further into Step functions and discovered an amazing service with endless implementation choices. 

**Thoughts:** I like CDK, which I'm sure it's here to stay! Another rhyme, another day :) (yesterday it was "CDK abstracts away" :P)

**Links:**

1. [CDK workshop](https://cdkworkshop.com/)

### Day 5: February 5, 2021

**Today's Progress:** I started to look into Corda, as a blockchain implementation for business commercials. Fascinating new world, learned lots of new concepts which I didn't know anything about. Determined to go deep into it and manage to help operationalize such a network.

**Thoughts:** You have to try new things to give yourself the change to experiment new concepts and ideas you didn't think about up to that point. Blockchain is a very elegant way to ensure persistent state through a decentralized database architecture.

**Links:**

1. [Corda education of Vimeo](https://vimeo.com/showcase/4555732)
2. [Corda - An Introduction whitepaper](https://docs.corda.net/en/pdf/corda-introductory-whitepaper.pdf)
3. [Corda - A Distributed Ledger](https://docs.corda.net/en/pdf/corda-introductory-whitepaper.pdf)
