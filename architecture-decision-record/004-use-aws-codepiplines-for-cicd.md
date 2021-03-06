  # 4. Use AWS CodePipelines for CI/CD
  Date: 2020-05-13

  ## Status
  β Accepted

  ## Context

We need a [CI/CD](https://en.wikipedia.org/wiki/CI/CD)β solution to support [PTTP](https://ministry-of-justice-acronyms.service.justice.gov.uk/#:~:text=Info-,PTTP,-Prison%20Technology%20Transformation) teams when deploying infrastructure and services into AWS.

  ## Decision

We have decided to use AWS CodeBuild and CodePipeline for [CI/CD](https://en.wikipedia.org/wiki/CI/CD)β. Itβs a fully managed service from Amazon Web Services and provides the following benefits.

- Native integration with AWS cloud estate SDK and CDK.
- Cross AWS account support
- Support for AWS Parameter Store
- Pipelines can be defined as YAML in a central repository


