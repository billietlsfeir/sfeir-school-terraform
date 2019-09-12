# Sfeir Institute Terraform
## Module-3b: Interpolations, looping and conditions
#### Objective : 
As a user, I would like to push 2 configurations files in cloud storage in order to create VMs using *startup-script-url*.

Do it using :
* the old way (using count terraform 0.11)
* Using new terraform 0.12 for_each way.

*Hints* : Refer to `google_storage_bucket` and `google_storage_bucket_object` to create bucket and to put objects.

Once the 4 objects are created (2 with `count`, 2 with `for_each`), add a new config file `"config-pp"   = "env = pp"`. 

What's happened when you run again `terraform plan` ?