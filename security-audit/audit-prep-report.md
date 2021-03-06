# Audit Prep Report

## What is an Audit Prep Report?

An Audit Prep Report is the summary report of the package presented to the auditor from the development team.  It is written just before the audit and is designed to assist the auditor with specific information they should know for the audit.

## Why do an Audit Prep Report?

This report summarizes all the important information the auditor needs to start their audit that is not documented elsewhere.

## What inside an Audit Prep Report?

### Audit Goals

These are the specific goals for this particular audit.  It can outline exactly what is to be audited. Any elements that should be ignored can be indicated here.

You should also include a discussion on the level of risk your application will experience. This is an estimate of the amount and value of any assets your application will contain and the time period it will contain those assets for. This will aid the auditor in understanding your risk level.

### Development Environment Information

This section should note the location of the scripts used to compile the application and run any tests. You must also include all version information of the compiler and any tools used. You should also include the location of the repository, if it is public. Normally this information would be referenced in the project README.

Remember to clean up your repository and organize the folders with clear names.  If needed explain the folder structure.

### Tool and Code Review Results

If you have run any [testing tools](../tools/existing-tools.md) on your code, this section should point to the results of those tools, as well as the scripts and options used when the tools were run. You should also provide commentary on your interpretation of these results and a discussion of any false positives you encountered in a [tool report](test-results/tool-reports.md) specific to each tool that was run.

### Test Results

This section gives the location in the repository for your [test results](test-results/). It should include a README that defines exactly how to run the test suite. This will include the results of [code coverage](test-results/coverage.md), and any explanations that are needed to explain the existence of any dead code. Any explanations the developer wishes to give to the auditor about any of the test failures should be listed or referenced here.

### Bug Bounty

Bug Bounties are a popular process for improving code after the audit but before full deployment.  Describe any bug bounty plans for your application and when they will take place.

### Deployment Plan

You should allow the auditors to comment on your [deployment plan](../deployment/deployment-plan.md).  It is an area where their experience could add significant value. Do you plan a limited test network release?  Discuss the top level plan. Do you plan a limited main net deployment? The limitations may impact your code. Describe the order you plan to deploy your contracts and the specific options with each deployment.

