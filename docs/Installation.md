# Installation

## Requirements

* [Terraform](https://www.terraform.io)
* Go >= 1.12 (for compiling)

## From source

You can either download the source code from github and `make` it or just run these commands:
 
```bash
$ mkdir -p $HOME/.terraform.d/plugins
$ # with go>=1.12
$ go build -v -o $HOME/.terraform.d/plugins/terraform-provider-kubeadm \
    github.com/inercia/terraform-provider-kubeadm/cmd/terraform-provider-kubeadm
$ go build -v -o $HOME/.terraform.d/plugins/terraform-provisioner-kubeadm \
    github.com/inercia/terraform-provider-kubeadm/cmd/terraform-provisioner-kubeadm
```

