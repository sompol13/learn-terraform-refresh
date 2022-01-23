## Use Refresh-Only Mode to Sync Terraform State
In this tutorial, you will safely refresh your Terraform state file using the `-refresh-only` flag. You will also review Terraform's implicit refresh behavior and the advantages of the `-refresh-only` flag over the deprecated `terraform refresh` subcommand.
- Run terraform plan `-refresh-only` to review how Terraform would update your state file.

<img width="278" alt="-refresh-onyl" src="https://user-images.githubusercontent.com/33342822/150661171-e8d05168-f30f-4c00-9be9-4e3a9f1c313c.png">

### Reference
https://learn.hashicorp.com/tutorials/terraform/refresh
