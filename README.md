# Beanstalk-permissions-with-Terraform

When you create an environment, AWS Elastic Beanstalk prompts you to provide two AWS Identity and Access Management (IAM) roles: a service role and an instance profile. When using the AWS console user is prompted to create these roles. These roles are not mentioned in the Terraform AWS provider website,  if these roles were not created before, Terraform apply fails. 
