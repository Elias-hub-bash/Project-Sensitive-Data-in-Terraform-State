Sensitive Data in Terraform State

Terraform state can contain sensitive data depending on the resources used. 
Sometimes it can contain initial database passwords or other secret data returned by a provider.
Every time you deploy infrastructure with Terraform it stores lots of data about that infrastructure including all the parameters you passed in, within the state file.
We recommend that you protect Terraform state as you would any other sensitive piece of data.

   1: View state file in raw format
   2: Suppress sensitive information
   3: View the Terraform state file
