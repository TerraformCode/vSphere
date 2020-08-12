# vSphere

## Prerequisites
### Installing the vSphere Terraform Provider

To start using the vRA Terraform provider you’ll need to have Terraform and Go installed on your local machine.

    mkdir -p ~/.terraform.d/plugins
    
    wget https://releases.hashicorp.com/terraform-provider-vsphere/1.22.0/terraform-provider-vsphere_1.22.0_windows_amd64.zip
    
    tar xvf terraform-provider-vsphere_1.22.0_windows_amd64.zip
    
    mv terraform-provider-vra ~/.terraform.d/plugins

Move the provider file plugin folder.
