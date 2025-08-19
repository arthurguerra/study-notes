# Módulo 4 - AWS Cloud Security

AWS is responsible for the security **OF** the cloud while
clients are responsible for the security **IN THE** cloud

Infrastructure as a Service (IaaS): client is responsible for the security of the resources
- Amazon EC2
- Amazon EBS
- Amazon VPC

Platform as a Service(Paas): AWS is responsible for the security 
- AWS Lambda
- Amazon RDS
- AWS Elastic Beanstalk

## AWS Identity and Access Management (IAM)

There are four IAM components
- User: person or aplication that is allowed to access the AWS account. Each user must have a unique login (name and password).
- Group: efficiency mechanism to apply permissions.
- Policy: document which defines access to one or more services. Policies are create independently of users and groups.
- Role: mechanism for granting temporary access to services.

#### Types of access
- Programatic Access: the user must present a key pair (access key ID and secret access key).
- Management Console Access: the user must at least fill their name and password. If multifactor authentication they would also be asked for the MFA code.

#### Authorization: 
The process of determining the permissions a user, service or application should be granted.

#### IAM Policy
Is a document writen in JSON (JavaScript Object Notation) that lists the permissions that allow or deny access to services.
- Identity based policies: can be attached to and entity (user, group or role)
- Resource based policies: attached to a resource