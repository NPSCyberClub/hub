# Your Battle Station

If you spend any more than about five minutes doing cybersecurity, you will likely want to develop your own dedicated computing environment to perform tasks in this space.
While we do browse the internet and process text documents, we also perform many other specialized tasks. A general-purpose computing environment is suboptimal.
To this end, platforms such as TryHackMe and HackTheBox do offer cloud-based, on-demand virtual machines for your use. They have them prepared with many tools and resources; however, you are, more or less, locked in to their dedicated instance if you choose to rely on this offering.

You may want to consider setting up your own local virtual machine, dedicated computer, or cloud instance for the sole purpose of doing CTFs and security research and such. There are many paths here, but Kali Linux and Parrot are two common choices. These Operating Systems come with many tools already installed to make your life easier. THM and HTB will provide you VPN connectivity which will allow you network access to their challenges while using your own attack infrastructure. Any customization you make can now advantage you no matter which CTF or training platform you use, so long as they provide you VPN access.

## Local Virtual Machine (VM)

A local VM allows you to run an instance of an entire Operating System from your current, host, system. The VM is known as a guest in this setup.
You will install a hypervisor which is an application that will allow you to run and manage guest VMs from your current, host system.

VirtualBox is the easiest to recommend. It is free and does not require an account. 

VMWare Workstation (for Windows) and VMWare Fusion (for macOS) are also options. You will need a Broadcom account.

## Cloud

You can also pay AWS, Azure, Digital Ocean, Linode, or others to host your environment. Each cloud provider has their own documentation and cost, but this can be a good option if you do not have the hardware or local storage yourself.

## Dedicated Device

You could also purchase or repurpose a dedicated computer, laptop or desktop, to serve as your hacking/CTF/research machine. This will provide good separation from your daily driver.

NOTE: For more specific help with getting set up, please do not hesitate to reach out to members on the Discord. Someone will be happy to help get you up and running. We know it can be a lot if this is your first time.
