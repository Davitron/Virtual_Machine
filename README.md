# Virtual_Machine
A windows virtual machine configured with Vagrant and Virtualbox

Vagrant is an open-source software product for building and maintaining portable virtual software development environments e.g. for VirtualBox, Docker containers, VMware, and AWS which try to simplify software configuration management of virtualizations in order to increase development productivity.

VirtualBox is a free and open-source hosted hypervisor for x86 computers currently being developed by Oracle Corporation. It may be installed on a number of host operating systems, including: Linux, macOS, Windows, Solaris, and OpenSolaris

Hypervisors are computer softwares, firmwares or hardwares that create and runs virtual machines.

## Prerequisite

To create a Windows server with this repository, Vagrant and Virtualbox have to be installed

- Install Homebrew from this [link](https://brew.sh/)

- Install Vagrant with the following command
  `brew install cask vagrant`

- Install Virtualbox with the following command
  `brew install cask virtualbox`

## Guidlines
- Clone the repository below on github, run the command below to do that

`git clone git@github.com:Davitron/Virtual_Machine.git`

- CD into Virtual_Machine directory
`cd Virtual_Machine`


- To build the windows OS, run
`vagrant up`

Depending on your network connectivity, This will most likeky take time since the size of the box is a little bit large. Ensure your internet connenction is stable.

`run virtualbox` to open the virtualbox UI and select the Windows machine click on the show button to open your windows OS

![Image 1](https://res.cloudinary.com/eventsmanager/image/upload/v1538003171/Screen_Shot_2018-09-26_at_11.48.30_PM_rbxgsm.png)

![Image 2](https://res.cloudinary.com/eventsmanager/image/upload/v1538003171/Screen_Shot_2018-09-26_at_11.49.19_PM_imezil.png)

![Image 3](https://res.cloudinary.com/eventsmanager/image/upload/v1538003173/Screen_Shot_2018-09-26_at_11.49.51_PM_xha9mj.png)
