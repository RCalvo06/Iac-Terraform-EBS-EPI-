# Iac-Terraform-EBS-EPI-

Terraform-EBS-EPI
En este ejemplo crearemos una máquina en ec2 simple con una clave SSH

Copia el fichero terraform.tfvars.examples
cp terraform.tfvars.example terraform.tfvars

Edita el fichero terraform.tfvars y pon tus propios valores, sobre todo el vpc_id y la clave ssh

Inicialización del despliegue
$ terraform init

Planificación del despliegue
$ terraform plan

Despliegue de la infraestructura
$ terraform apply

Conexión SSH
ssh -l ubuntu EIP

Destrucción de la infraestructura
$ terraform destroy
