Alicloud RAM User Creation Terraform Module
===

Terraform module which adds list of users with console logon and group membership. 
It assumes that you have RAM enabled already.

Usage
-----
You can use this in your terraform template with the following steps.

1. Adding a module resource to your template, e.g. main.tf:

```
 module "tf-security-group" {
    source = "alibaba/security-group/alicloud"
```

2. Setting values for the following variables in the variables file or through the environment variables:

    - ALICLOUD_ACCESS_KEY
    - ALICLOUD_SECRET_KEY
    
Authors
-------
Created and maintained by Sandor Kosztka (@kosztkas)

Reference
---------
* [Terraform-Provider-Alicloud Github](https://github.com/alibaba/terraform-provider)
* [Terraform-Provider-Alicloud Release](https://github.com/alibaba/terraform-provider/releases)
* [Terraform-Provider-Alicloud Latest Docs](http://47.95.33.19:4567/docs/providers/alicloud/)
