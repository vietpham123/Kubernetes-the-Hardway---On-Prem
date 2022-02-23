# Kubernetes-the-Hardway---On-Prem

This guide is designed to help people with learning how to deploy Kubernetes by going through all nuanced configurations needed to create a highly available cluster.  These instructions are modifications from Michael Champagne who did the original one on his blog, and Kelsey HightTower's Kubernetes the hardway done in AWS.

Target Audience

The target audience for this tutorial is someone planning to support a production Kubernetes cluster and wants to understand how everything fits together.

Cluster Details

Kubernetes The Hard Way guides you through bootstrapping a highly available Kubernetes cluster with end-to-end encryption between components and RBAC authentication.

kubernetes v1.21.0
containerd v1.4.4
coredns v1.8.3
cni v0.9.1
etcd v3.4.15
Labs

This tutorial is designed to be run On-Prem either as VMs or on bare metal. 

Prerequisites
Installing the Client Tools
Provisioning Compute Resources
Provisioning the CA and Generating TLS Certificates
Generating Kubernetes Configuration Files for Authentication
Generating the Data Encryption Config and Key
Bootstrapping the etcd Cluster
Bootstrapping the Kubernetes Control Plane
Bootstrapping the Kubernetes Worker Nodes
Configuring kubectl for Remote Access
Provisioning Pod Network Routes
Deploying the DNS Cluster Add-on
Smoke Test
Cleaning Up