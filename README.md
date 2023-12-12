# Broken JSON Launch Template

This code is used to fix a broken JSON launch template for AWS CloudFormation.

The purpose of this script is to parse the JSON file containing the launch template configuration,
identify any errors or inconsistencies, and make the necessary fixes to ensure the template is valid.

`original.json` is the original JSON file containing the broken launch template.

`fixed.json` is the fixed JSON file containing the launch template after it has been fixed.

Usage:

- Ensure that the JSON file path is correctly specified in the 'file_path' variable.
- Run the script to automatically fix the JSON launch template.

Note: This script assumes that the AWS CLI is installed and configured on the system.

Author: Nick Huemmer
Date: 12/10/2023
