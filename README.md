# Terraform Local State Backend


This repo contains simple Terraform Configuration with `null_resource` provider to test the local backend and `.gitignore` 

# Prerequisite

* Preinstalled [Terraform CLI >0.13](https://learn.hashicorp.com/tutorials/terraform/install-cli)

# How to use the repo

1. Clone locally:
```
git clone https://github.com/51r/Terraform-local-backend.git
```

2. Make sure that you are in the root directory:
```
cd Terraform-local-backend
```

3. Apply the plan:
```
terraform apply
```

4. Once the plan is executed, the local exec provisioner should print in the console "Hello World"
```
null_resource.helloWorld (local-exec): Executing: ["/bin/sh" "-c" "echo Hello World"]
null_resource.helloWorld (local-exec): Hello World
```
