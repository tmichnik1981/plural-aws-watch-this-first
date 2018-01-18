# Adopting AWS: Watch This First

#### Using Multiple Accounts

###### Why more than one account

- separate environments: production / development (phase)
  - when org. has separation of duties 
  - works with decentralized IT
  - monitor and alert by environment
  - levels of autonomy by development process
- break by project
  - when project based accountability
  - work well with DevOps
  - monitor and alert by project
  - levels of autonomy by project
- break by different business units 
  - when organization have the accountabilities by business unit
  - decentralized IT
  - monitor cost by BU
- tight security isolation
- failure boundaries
- central auditing

**Umbrella account** - single account for logs, auditing etc but not for billing

**Cross account login** using role based access controls

#### Securing Your Accounts

###### Singup and setup

- Use group email address
- Set contact information
- Set currency options

###### First User group and policy

- Do not use your root acoount
- IAM - who, can do what in a AWS account
- Create a group of users and assign policy to the group

1. Go to **IAM**
2. Click **Account settings** and tune your  **Password Policy**
3. Click **Groups**

