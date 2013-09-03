Crowbar Developers Guide
========================

This is the developers guide for Crowbar.

The guide is s currently under development, and changing rapidly.

The table of contents for the documentation 
will follow the outline below.

* crowbar concepts / architecture 
    * what is crowbar 
    * barclamps
    * jigs
	* Jig: “writing and integrating upstream cookbooks & modules”
    * Crowbar's state machine , the Annealer
	* Deployments, Nodes, Roles & the Annealer
    * crowbar builds / releases
    * ui 
    * web framework / rails 
    * network abstraction
    * heterogenous operating systems
    * state machine
    * pull from source 
    * database backend
    * sledgehammer
    * UEFI 

* crowbar development environment
    * code organization
    * build process overview
    * community development workflow 
        * branches, pull requests, etc
    * setting up a build VM
        * dev-vm-Fedora
        * dev-vm-SUSE
        * dev-vm-Ubuntu
    * Judd's vagrant build setup

    * devtool-build.md 
    * dev-vm
    * devtool
    * coding conventions 
    * how to write a new barclamp
    * packaging and installation
    * “how to build packages” – I thought packages was our primary output for CB2.0, not ISOs – allowing continuous deployment of crowbar itself.
        * how to build an ISO from existing code

* using crowbar for continuous deployment 
* testing and continuous integration

* documentation system
* api reference
    * api calls 