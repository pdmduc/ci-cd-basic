# The different between continuous integration and continious delivery.

## In business or technical terms describe your understanding of continuous integration and continuous delivery (CI/CD)?

### What exactly is continuous integration?

Continuous integration is the technique of integrating all code changes into the main branch of a shared source code repository often, automatically testing each change when it is committed or merged, and immediately initiating a build. Using continuous integration, defects and security vulnerabilities may be recognised and resolved considerably sooner in the software development lifecycle, and with more ease.

Multiple developers working on the same application can reduce the likelihood of code conflicts by merging changes often and initiating automated testing and validation procedures. A side benefit is that you do not have to wait long for responses and can, if necessary, repair bugs and security vulnerabilities.

Static code analysis is usually the first step in software testing to ensure the code is of sufficient quality. Automated CI routines package and compile the code for additional automated testing after it has passed the static tests. It is important to keep track of the code version that is being utilised in CI procedures by using a version control system.

### How about continuous delivery?

Continuous delivery is a software development approach that, when combined with continuous integration, helps to automate the process of releasing new versions of both infrastructure and applications.

Continuous delivery takes over the final steps of the CI process to ensure that the code is ready to be deployed to any environment at any time after it has been tested and built. From initial infrastructure provisioning through final application deployment in test or production, continuous delivery can take care of it all.

Continuous delivery entails designing software so that it can be delivered to production at any moment. When ready, you can either manually initiate the deployments or switch to continuous deployment, in which case the deployments will also be automated.

# What are some tools that are used for this and why are they used.

Software development teams might benefit from using CI/CD tools to automate the software creation and testing processes. Various techniques focus on different stages of the process, with some focusing on integration (CI), others on development and deployment (CD), and still others on continuous testing (or something similar). Below are some

1. Jenkins
   Jenkins, an automation server, is one of the most well-known open source solutions for continuous integration and continuous delivery (CI/CD). Jenkins was built to handle anything, from a basic continuous integration server to a comprehensive continuous delivery centre.

2. GitLab CI
   GitLab CI is a web application that maintains its state in a database and comes equipped with an API. In addition to providing the benefit of having all of GitLab's capabilities, it is also one of the top tools for managing projects and providing a user-friendly ui, making it one of the best tools for Continuous Integration.

# Reference Source

1. https://jenkins.io/
2. https://about.gitlab.com/topics/ci-cd/
3. https://www.redhat.com/en/topics/devops/what-is-ci-cd
