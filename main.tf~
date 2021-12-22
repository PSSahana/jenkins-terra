variable "vpcnaming"{
   type = string
   description =  "setname for vpc"
}

resource "aws_vpc" "myvpc" {
    cidr_block = "192.168.0.0/24"

    tags = {
      Name = var.vpcnaming
    }

  
} 