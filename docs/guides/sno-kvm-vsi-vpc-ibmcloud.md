# Install single node OpenShift on Linux-KVM Virtual Server for VPC on IBM Cloud

This guide uses a collection of Ansible playbooks that provisions a single node OpenShift cluster on Linux KVM on a Virtual Server for VPC on IBM Cloud using Red Hat Assisted Service (Software as a Service).

The playbooks are bundled into the following three modules:

* ic.vpc creates the VPC Infrastructure on IBM Cloud, including VPC, Subnet, Floating IP, Access Control List (ACL), Security Group, Floating IP,
* ic.vsi.kvm creates a Virtual Server instance (VSI) for VPC on IBM Cloud and install Rocky Linux with Linux-KVM hypervisor, and required SSH keys,
* ic.vsi.kvm.sno creates the required Virtual Machines (VMs) and install single node OpenShift (SNO) on KVM-Linux, including KVM guest users, for DNS and DHCP services, HAProxy.

For the complete installation guide go to [https://github.com/IBM/sno-on-ibm-cloud-vpc-ansible](https://github.com/IBM/sno-on-ibm-cloud-vpc-ansible).
