# nsx_certificates_cookbook
This repository includes all the scripts part of the NSX Certificates Management cookbook published on [VMware communities](https://communities.vmware.com/t5/VMware-NSX-Documents/NSX-Certifcates-Management-Cookbook/ta-p/2992832)
The script has been added to this repository as the copy and paste from the PDF document produces formatting errors.

The only requirements to run the scripts are bash and [jq](https://jqlang.github.io/jq/). You can install jq via the usual package manager of your system (i.e., homebrew or apt)

# Table of contents (use it to find the corresponding script)

## 1	Introduction

1.1	Scope of the document

1.2	Additional Resources

## 2	Overview of the NSX Certificates

2.1	API/UI Certificates

2.2	APH-TN, CCP, APH-AR Certificates

2.3	Local manager and Global Manager Certificates

2.4	CBM certificates

2.5	Transport Nodes Certificates

2.6	Principal Identity Certificates

2.7	Summary of the certificates in a Local Manager NSX Cluster

2.8	Summary of the certificates in a Global Manager NSX cluster

2.9	NSX Certificates Best practices

2.10	Impact of certificate expiration

## 3	Recipes

### 3.1	Singleton NSX Manager

3.1.1	Replacing API/UI Certificates with a self-signed certificate

3.1.2	Replacing Local Manager Certificate with a self-signed certificate

3.1.3	Replacing  APH-AR, APH-TN and CCP certificates with self-signed certificates

3.1.4	Replace Corfu Client Certificates

3.1.5	Replace Corfu Server Certificate

3.1.6	Delete Unused certificates

### 3.2	Three node cluster NSX Manager

3.2.1	Replacing API/UI Certificates with a self-signed certificate

3.2.2	Replacing Local Manager Certificate with a self-signed certificate

3.2.3	Replacing APH-AR, APH-TN and CCP certificates with self-signed certificates

3.2.4	Replacing Corfu Client certificates

3.2.5	Replace Corfu Server Certificate

3.2.6	Delete Unused certificates

### 3.3	Global Manager 3 node cluster

3.3.1	Replacing API/UI Certificates with a self-signed certificate

3.3.2	Replacing Global Manager Certificate with a self-signed certificate

3.3.3	Replacing  APH-AR and APH-TN certificates with self-signed certificates

3.3.4	Replacing corfu clients certificates

3.3.5	Replace Corfu Server Certificate

3.3.6	Delete Unused certificates

### 3.4	Transport Node Certificates

3.4.1	Replacing a TN certificate via the NSX API

3.4.2	Replacing a TN certificate manually

3.4.3	Retrieve validity of the TN certificates currently in use

### 3.5	Principal Identities Certificates

3.5.1	Create PI with corresponding self-signed certificate

3.5.2	Update certificate of existing PI

### 3.6	Additional Recipes

3.6.1	Import a CA signed certificate via the API (CSR Generated outside of NSX)

3.6.2	Import a CA signed certificate via the API (CSR Generated in NSX)

3.6.3	Generate and import a self-signed certificate generated outside of NSX

3.6.4	Verify certificate replacement via opensll on a specific port

3.6.5	Manage Corfu certificate expiry check

