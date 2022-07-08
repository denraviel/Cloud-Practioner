IAM users cannot access billing data until the account owner activates IAM access and also attaches policies that provide billing actions to the user or role so I enabled access to billing data to IAm user from my root account
To activate IAM user and role access to the Billing and Cost Management console,I Signed in to the AWS Management Console with my root account credentials
On the navigation bar,I chose my account name, and then choose My Account.
Next to IAM User and Role Access to Billing Information,I chose Edit
I Selected the Activate IAM Access check box to activate access to the Billing and Cost Management console pages and updated changes.
I can now use IAM policies to control which pages a user can access

To create IAM policies that grant permissions to billing data
I created a policy "BillingFullAccess" to allow full access to billing on the account
I Created another policy "BillingViewAccess" to allow Read-only access

I made two groups, BillingViewAccessGroup and BillingFullAccessGroup, and I attached to each of them the corresponding BillingViewAccess and BillingFullAccess policies.
I created two test users FinanceManager and FinanceUser, added FinanceManager to BillingFullAccessGroup and added FinanceUser to BillingViewAccessGroup

I logged out of my admin account and tested both users respectively.