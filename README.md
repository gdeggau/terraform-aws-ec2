# Terminal commands

Initialize a working directory

    terraform init

Preview the changes made

    terraform plan

Apply changes

    terraform apply

Validate if code is correct

    terraform validate

Show all the states/resources

    terraform state list

See details of a state/resource

    terraform state show aws_instance.ec-vm

Destroy all the states/resources created in cloud

    terraform destroy -auto-approve
