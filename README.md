# Import AWS IAM into Cloudformation

Example of importing an IAM Role into Cloudformation

## Summary

This is working code that was created while following this documentation:

- https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/resource-import-new-stack.html#resource-import-new-stack-cli
- https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/resource-import.html

## Prerequisites

First install a Python3 environment and the `requirements.txt`.

The [templates/001.yaml](templates/001.yaml) template matches an example Lambda Role that was manually created in AWS with 2 managed policies attached. The [notebooks/scratchpad-no-output.ipynb](notebooks/scratchpad-no-output.ipynb) has example commands and the documentation for how to import the IAM Role to CFN and notes about the status at each step.
