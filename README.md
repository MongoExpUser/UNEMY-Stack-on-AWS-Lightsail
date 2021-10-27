
[![CI - UNEMY](https://github.com/MongoExpUser/UNEMY-Stack-on-AWS-Lightsail/actions/workflows/cdk-terraform-unemy.yml/badge.svg)](https://github.com/MongoExpUser/UNEMY-Stack-on-AWS-Lightsail/actions/workflows/cdk-terraform-unemy.yml)
# UNEMY-Stack-on-AWS-Lightsail

<br>
<strong>
Deploys Ubuntu, NodeJS, ExpressJS and MySQL (UNEMY) Stack on AWS Lightsail with Terraform Python CDK..
</strong>
<br><br>
The  STACK deploys the following specific resources and software:

1) AWS Lightsail ssh key pair, assigned to instance(s) in Item 2 below.
                                                                                                                                                 
2) AWS Lightsail instance(s) with Ubuntu 20.04 LTS OS
                                                                                                                                                 
3) AWS Lightsail static ip(s) for the instance(s).
                                                                                                                                               
4) AWS Lightsail static ip attachhment(s) to the instance(s).

5) Bash launch or start-up script (user data) for the installation of software, on the instance(s), including:

   -  Additional Ubuntu OS Packages <br>
   -  NodeJS <br>
   -  ExpressJS Web Server Framework <br>
   -  Other Node.js Packages and <br>
   -  MySQL

## DEPLOYING THE CDK STACK

1) To deploy the stack  on ```AWS``` via local computer, follow the steps in the following link:<br>
 <strong>CDK for Terraform Application</strong>: <a href="https://learn.hashicorp.com/tutorials/terraform/cdktf-build-python?in=terraform/cdktf" rel="nofollow">https://learn.hashicorp.com/tutorials/terraform/cdktf-build-python?in=terraform/cdktf</a></p>
  
2) To deploy the stack  on ```AWS``` via <strong>GitHub Actions</strong> see the following link: <br>
<strong>GitHub Actions CI</strong>: <a href="https://learn.hashicorp.com/tutorials/terraform/cdktf-build-python?in=terraform/cdktf" rel="nofollow">https://github.com/MongoExpUser/UNEMY-Stack-on-AWS-Lightsail/blob/main/.github/workflows/cdk-terraform-unemy.yml
l</a></p>
  

# License

Copyright © 2015 - present. MongoExpUser

Licensed under the MIT license.
