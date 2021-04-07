# HashiCat - Azure

A HashiCorp Terraform built web application for use in HashiCorp demos and workshops.

### Prerequisites

<img src="https://logodix.com/logo/745893.png" alt="Azure" width="200"/>

First and foremost, an [Azure](https://azure.microsoft.com/en-us/) account will be needed. The Terraform configuration will need values for the following variables for which Azure resources should be created: 
- subscription_id
- client_id
- client_secret
- tenant_id

<img src="https://www.datocms-assets.com/2885/1603728375-blog-library-product-terraform-cloud.jpg" alt="Terraform Cloud" width="200"/>

Also required, a place to run terraform operations. These options include:
- [Terraform Cloud](https://app.terraform.io) - includes the ability to run Terraform operations remotely, securely store state files, and more!
- [Terraform Open Source](https://www.terraform.io/downloads.html) - an open source binary which can be executed locally 

The only other requirement would be input for the variable of "prefix" which is used when naming the different resources involved. 

### Gratuitous Cat Image

[![Cat Image](http://placekitten.com/g/400/200)]

### Test Status

[![CircleCI](https://circleci.com/gh/hashicorp/hashicat-azure/tree/master.svg?style=svg)](https://circleci.com/gh/hashicorp/hashicat-azure/tree/master)
