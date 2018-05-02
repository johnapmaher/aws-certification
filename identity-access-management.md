# IAM - Identity Access Management

IAM covers user management and access control.

* Share your AWS account with others.
* Identity Federation with Active Directory & others, including social login.
* Multi factor authentication.
* Provide tempory access to users.
* Set up password rotation policies
* Supports PCI/DSS compliance.

# IAM consists of the following
* Users
* Groups - a means to group users and apply policy to them collectively.
* Roles
* Policy Documents - JSON list of access parameters.

# IAM is a global configuration
* It's the same configuration across all regions
* The root account is the account that created the aws account
* New users have no permissions
* New users are assigned an Access Key ID & Secret Access Key
 - these are downloadable by .csv
* You can only view these keys at time of creation unless downloaded for safekeeping.
* It's good practive to set up multifactor authentication - google authenticator is used on iOS and Android.
* You can create password policys in the IAM console.
