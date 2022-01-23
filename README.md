## Use Refresh-Only Mode to Sync Terraform State
In this tutorial, you will safely refresh your Terraform state file using the `-refresh-only` flag. You will also review Terraform's implicit refresh behavior and the advantages of the `-refresh-only` flag over the deprecated `terraform refresh` subcommand.
- Run terraform plan `-refresh-only` to review how Terraform would update your state file.

### Reference
https://learn.hashicorp.com/tutorials/terraform/refresh