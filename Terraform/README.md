## Criar uma infraestrutura na Amazon AWS utilizando o Terraform
   * Subir 1 instância EC2 t2.micro com EBS attached de 20GB na rede pública
   
`vpc.tf`: Responsável por criar a VPC e também subnets Pública e Privada

`variables.tf`: Declaração das variáveis

`public.tf`: Criar as 1 instância com disco de 20GB atachado e atrelado à subnet pública

`provider`: Faz a conexão com a AWS
