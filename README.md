# CSAIL Openstack Terraform

*forked from [terraform-openstack-examples](https://github.com/diodonfrost/terraform-openstack-examples)*

# Authentication

```terraform
provider "openstack" {
  user_name   = "my-litle-user"
  tenant_name = "my-little-tenant"
  password    = "secret"
  auth_url    = "http://your-cloud-prodivder.com"
}
```


