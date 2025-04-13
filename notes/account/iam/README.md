# Identity and Access Management (IAM)

- [Identity and Access Management (IAM)](#identity-and-access-management-iam)
  - [AWS Root User](#aws-root-user)
  - [Objects that can be created](#objects-that-can-be-created)
  - [Resilience](#resilience)
  - [Least Privilege](#least-privilege)
  - [Users](#users)
  - [Groups](#groups)
  - [Roles](#roles)
  - [Policy Document](#policy-document)

IAM lets you manage identities for an AWS account. Each AWS account comes with its own IAM database. The IAM of an account has **full trust** just like the root user.

## AWS Root User
Essentially, the root user is synonymous with the *account*. It cannot be restricted.

**Note:** You should use other users for most operations.

## Objects that can be created
- Users
- Groups
- Roles

## Resilience
IAM is *Globally Resilient*, meaning data is secure across **all** AWS regions.

## Least Privilege
Users should be granted the **least** amount of privileges to complete assigned job.

## Users
Humans or applications that need access to the AWS account.

## Groups
Collections of related users (i.e. IT Department, Engineers, etc.).

## Roles
Used when you need to grant an *uncertain number of identities* to a set of services. Roles can be used by AWS services or if you want to grant access to the AWS account.

Roles allow AWS services to act on your behalf.

## Policy Document
A policy document can be attached to certain roles, groups, or users to control access.

