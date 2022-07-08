In an organization demo.io, they have 5 people in different unit as listed:

I logged out of my root account and signed in with my IAM admin user
On my IAM dashboard, I changed Account Alias to demo_io to reflect the name of the organization.
Admin Support
I created user Gbenga and added the user to the Admin group as admin support.

Tech Team
Created another user group "TechTeam" attached System Administrator Policy to the group and added user "Dele" to the group.The SystemAdministrator policy grants full access permissions necessary for resources required for application and development operations. I allowed Programmatic access and AWS Management Console access for the user since it enables an access key ID and secret access key for the AWS API, CLI, SDK, and other development tools.

I also created another user "Ade" under Techteam group as Technical support and also granted Programmatic access and AWS Management Console access

Storage Group
Created a group storage group and added user "Segun" to the group, granted aws management console access. I also attached DatabaseAdministrator policy.This policy grants full access permissions to AWS services and actions required to set up and configure AWS database services.

Lastly,
Finance Head
Created Finance group added user sharon as finance head.granted aws management console access. I also attached Billing policy.This policy grants permissions for billing and cost management. This includes viewing account usage and viewing and modifying budgets and payment methods.