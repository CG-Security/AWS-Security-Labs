# Lab 3 – Creating Access Keys in AWS IAM for CLI Configuration

This lab demonstrates how to create and securely configure IAM access keys for AWS CLI use. It includes verifying the setup through command-line interaction and ensuring that no sensitive credentials are exposed.

---

## Objective
Generate IAM access keys for AWS CLI access, configure them securely on a local system, and verify successful authentication using command-line operations.

---

## Steps Performed
1. Opened the IAM console and selected an existing IAM user account.  
2. Created a new set of Access Keys for programmatic access.  
3. Blurred or redacted all key values to ensure credentials were not exposed in documentation or screenshots.  
4. Configured the AWS CLI using the generated access keys with the following command: `aws configure`  
5. Entered the Access Key ID, Secret Access Key, default region, and output format when prompted.  
6. Verified successful configuration by listing IAM users using the command: `aws iam list-users`  
7. Confirmed valid credentials and CLI connectivity through successful user listing output.

---

## Key Takeaways
- Never expose or store plain-text access keys in documentation or shared repositories.  
- Use the `aws configure` command to securely store credentials in the AWS CLI profile.  
- Always verify setup with safe read-only commands like `aws iam list-users`.  
- Rotate or delete unused access keys periodically for better security hygiene.

---

## Screenshots

