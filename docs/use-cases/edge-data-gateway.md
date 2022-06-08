# Use Case: Edge Data Gateway

## Overview

Devices on the edge can be small appliances that function as a data gateway. A edge data gatewaty may run on a single node device as small as 2 cores with 4Gb RAM (2x4). To still profit from container and container orchestration like Kubernetes, you need an optimized edition of Kubernetes or OpenShift that can run on a single node cluster, like single node OpenShift (SNO) or MicroShift.

## Ansible

This use case uses a collection of Ansible playbooks that provisions a Single Node OpenShift cluster on Linux KVM on IBM Cloud using Red Hat Assisted Service.

## Installation Guide

See [Install single node OpenShift on Linux-KVM Virtual Server for VPC on IBM Cloud](../guides/sno-kvm-vsi-vpc-ibmcloud.md).
