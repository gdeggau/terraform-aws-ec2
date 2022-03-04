# Terminal commands

Initialize a working directory

    terraform init

Format files

    terraform format

Preview the changes made

    terraform plan

Apply changes

    terraform apply

Preview the changes made and save in a file

    terraform plan -out="plan.tfout"

Apply changes saved in a file

    terraform apply "plan.tfout"

Validate if code is correct

    terraform validate

Show all the states/resources

    terraform state list

See details of a state/resource

    terraform state show aws_instance.ec-vm

Destroy all the states/resources created in cloud

    terraform destroy -auto-approve

Show sensitive output

    terraform output db_password
