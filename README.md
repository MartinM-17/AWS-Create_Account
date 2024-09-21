# Create_AWS_Account

## Objective

This exercise provides hands-on experience in creating and managing users and roles in AWS using IAM (Identity and Access Management).

## Steps Detailed

### 1. Create an AWS Account

- Navigate to [aws.amazon.com](https://aws.amazon.com).
- Follow the steps to create an account by providing the required information.

### 2. Verify the Account

- Follow the instructions in the verification email sent by AWS.

### 3. Access the AWS Console

- Go to [aws.amazon.com/console](https://aws.amazon.com/console).
- Log in using the credentials for the root account.

### 4. Create an Admin Group

- Navigate to IAM.
- Select "User groups."
- Create a new group named `AdminGroup`.
- Attach the `AdministratorAccess` policy.

### 5. Create an Admin User

- In IAM, select "Users."
- Add a new user named `AdminUser`.
- Select "Programmatic access" and "AWS Management Console access."
- Set up a password for the user.
- Add the user to the `AdminGroup`.

### 6. Create a Billing User

- In IAM, select "Users."
- Add a new user named `BillingUser`.
- Select "AWS Management Console access."
- Set up a password for the user.
- Attach the `Billing` policy.

### 7. Grant Billing Permissions to BillingUser

- Navigate to "My Account."
- Edit "IAM User and Role Access to Billing Information."
- Enable IAM access to billing information.

## Conclusion

The creation and management of users and roles in AWS were successfully completed by following the outlined steps.
