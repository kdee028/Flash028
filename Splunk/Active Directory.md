Install Active Directory Domain Services
- What is a Domain Controller?
A Domain Controller (DC) is a server that runs Active Directory. It is the brain of the entire identity system. When a user logs in anywhere on the domain, their credentials are checked against the Domain Controller. When you create a user account, you create it on the Domain Controller. There is usually more than one in an enterprise for redundancy, but we are building one here. Everything that joins your network will trust this server to make authentication decisions.

In Server Manager, click Manage → Add Roles and Features. Click Next through the wizard until you reach Server Roles. Check Active Directory Domain Services. When prompted, click Add Features to include the management tools. Click Next through the remaining pages and click Install. Wait for installation to complete — takes 2–3 minutes. When complete, click Close — do not restart yet.
