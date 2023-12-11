# VXLAN and VTEPs

<!-- toc -->

- [Description](#description)
- [Initialization](#initialization)

<!-- tocstop -->

## Description

Lab environment to help me better understand VTEPs, VXLAN and L2VPN/EVPN BGP.

## Initialization

- Run `make http-server` at the root of the repository to provide a temporary webserver for auto-installation of our VMs.
- Recurse through the `vtep[0-9]` directories and run the `vtep[0-9].sh` shell script invoking the creation of a VM.
- Run `make ansible` to configure the VMs.