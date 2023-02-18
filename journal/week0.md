# Week 0 — Billing and Architecture

## Create an IAM user

AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. With IAM, you can centrally manage permissions that control which AWS resources users can access. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.

* Sign in to the AWS Management Console with your root account credentials. Navigate to the IAM service console.
* Choose "Users" in the left-hand menu, then click the "Add user" button.
* Enter a name for the user in the "User name" field.
* Select the "Programmatic access" and/or "AWS Management Console access" to grant the user access to AWS resources via the AWS CLI, SDKs, or the AWS Management Console.
* Choose "Next: Permissions".
* In the "Set permissions" step, grant budget and cost alert permissions.
* Click on the "Permissions" tab and click the "Attach policies" button.
* Select "AWSBudgetsFullAccess" policy.
* Click on "Attach policy". The "AWSBudgetsFullAccess" policy grants the user full access to create, edit and delete budgets and also to receive budget notifications.
* Click "Next: Tags" to add tags to the user (optional).
* Choose "Next: Review" to review your settings, then create user.

## To activate IAM user and role access to the Billing and Cost Management console


* Sign in the AWS Management Console with your root user credentials (using your email address and password).

* On the navigation bar, choose your account name, and then choose Account.

* Next to IAM User and Role Access to Billing Information, choose Edit.

* Select the Activate IAM Access check box to activate access to the Billing and Cost Management console pages.

* Choose Update.

[AWS Official Documentation](https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_billing.html?icmpid=docs_iam_console#tutorial-billing-step1)