# K8S-Cluster-on-Raspberry-Pi-3

Set up Kubernetes 1.9.0 cluster on four Raspberry Pi 3 b+ using Kubeadm : one for master node and the other three for worker nodes. Such a cluster is expected to be able to scale up for further applications. This project will guide you through the process of setting up a Raspberry Pi Kubernetes cluster on the latest version of Raspbian, and with the latest version of Kubernetes as well.

This project is inspired [great work](https://kubecloud.io/setup-a-kubernetes-1-9-0-raspberry-pi-cluster-on-raspbian-using-kubeadm-f8b3b85bc2d1) by Kasper Nissen. 

## Get started with Raspberry Pi

To get started with Raspberry Pi, an operating system, **NOOBS (New Out Of Box Software)**, is required to be installed.
- **Buy preinstalled SD card**
- **Download from the [website](https://www.raspberrypi.org/downloads/)**

More detailed installation steps can be seen [here](https://www.raspberrypi.org/help/noobs-setup/2/).

> NOTE: When formatting the SD card, it is recommended to use [MiniTool Partition Wizard](https://www.partitionwizard.com/free-partition-manager.html) to format it as FAT32.

> NOTE: The default keyboard configuration is not *`us`*. First, open “/etc/default/keyboard” with nano `sudo nano /etc/default/keyboard`. Then edit `XKBLAYOUT` line into *`us`*. Finally, reboot the raspberry pi `sudo reboot`.

## Initial setup of SD-cards and prerequisites for Kubernetes

To be continued ...

### Flash the SD card

To be continued ...

### Change the hostname and assign a static IP

To be continued ...

### Install the prerequisites

To be continued ...

## Initialize the Kubernetes master

To be continued ...

## Set up the worker nodes

To be continued ...

## Set up the container network


To be continued ...
