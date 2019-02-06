# packer-oci
Build OCI images with packer

Workshop builds a client image through a series of steps to show how packer automates installation and configuration tasks.

Welcome to the **Oracle Cloud Infrastructure**   building OCI images with Packer workshop. This workshop will walk you through the process of creating an custom infrastructure image, similar to a VM, to support a varity of DevOps and production use-cases.  Packer allows this image to be built - as code... a small JSON file.  This increases effiency as the same image can be built on different cloud provides (AWS, Oracle, GCP), or Virtualbox or VMWare in on-premise environments.

As part of this workshop, you will complete labs helping you to better understand:

- Configuring OCI Infrastructure to support an Image
- Launching an image and installing software (packer and git)
- Using Packer and Git to build a custom OCI image which is configured to support a desktop login via VNC, firewall configuration and a custom environment (alias setup and variables)

