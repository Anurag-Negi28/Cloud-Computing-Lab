# Experiment: Introduction to AWS Identity and Access Management

## Objective

To understand and implement AWS Identity and Access Management (IAM) by creating users, assigning permissions, and verifying access.

## Steps

### 1. Create Users

Create the following users with specified permissions:

- **anurag-user1**: EC2 read-only access
- **anurag-user2**: EC2 full access
- **anurag-user3**: S3 bucket full access

Take screenshots for each step.

### 2. Create User Groups

Create the following user group and assign permissions:

- **group1**: EC2 full access permission

### 3. Assign Users to Groups

Assign `anurag-user1` to `group1`.

### 4. Verify Permissions

Check if `anurag-user1` can launch an EC2 instance as it is in `group1` which has EC2 full access.

## Expected Outcome

- `anurag-user1` should be able to launch an EC2 instance.
- `anurag-user2` should have full access to EC2.
- `anurag-user3` should have full access to S3 buckets.

## Documentation

Include screenshots for each step to verify the creation of users, user groups, and the assignment of permissions.
