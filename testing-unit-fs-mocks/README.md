[![Deploy this example with Pulumi](https://www.pulumi.com/images/deploy-with-pulumi/dark.svg)](https://app.pulumi.com/new?template=https://github.com/pulumi/examples/blob/master/testing-unit-fs-mocks/README.md#gh-light-mode-only)
[![Deploy this example with Pulumi](https://get.pulumi.com/new/button-light.svg)](https://app.pulumi.com/new?template=https://github.com/pulumi/examples/blob/master/testing-unit-fs-mocks/README.md#gh-dark-mode-only)

# Unit Testing Pulumi programs in F#

An example of writing mock-based unit tests with both infrastructure definition and tests written in F#.
The example uses the [NUnit](https://nunit.org/) test framework to define and run the tests and [FluentAssertions](https://github.com/fluentassertions/fluentassertions) for assertions.

It defines a stack that deploys a static website to Azure Storage and a suite of tests to validate the deployment. It also shows several examples of changing mocks for the testing needs.

## Prerequisites

[Install .NET Core 3.1+](https://dotnet.microsoft.com/download)

## Running the tests

Run the tests:

```
$ dotnet test

Microsoft (R) Test Execution Command Line Tool Version 16.3.0
Copyright (c) Microsoft Corporation.  All rights reserved.

Starting test execution, please wait...

A total of 5 test files matched the specified pattern.

Test Run Successful.
Total tests: 5
     Passed: 5
 Total time: 1.2167 Seconds
```

## Further steps

Learn more about testing Pulumi programs:

- [Testing Guide](https://www.pulumi.com/docs/guides/testing/)
- [Unit Testing Guide](https://www.pulumi.com/docs/guides/testing/unit/)
