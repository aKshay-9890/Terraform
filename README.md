# Terraform
whenever the infrastructure is modified it compares ot with the statefile. In state file all sensetive information is store and it secures it.
statefile is created after terraform apply 
# How do you manage statefile ? 
# Provisioner => in terraform, provisioner are a set of built-in functionalities that allow you to execute scripts, commands, or other configuration action on remote resources 
Types of Provisioner: 
1. file
2. local exec
3. remote exec

# Terraform Workspace :
commands:
terraform workspace select <workspace-name>
terraform workspace show        (it shows current workspace)
terraform workspace list        (list all the workspaces)     
terraform workspace new <workspace-name>   (to create new workspace)
