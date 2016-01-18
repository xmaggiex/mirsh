mirsh is a Multi-vIRSH tool allowing to perform some virsh-like commands on a "pool" of kvm hosts.

Requirements:
* One or more properly configured kvm host(s) with libvirtd/virsh.
* Passwordless ssh between all kvm hosts.
* An /etc/kvmhosts file with a resolvable names of all pool members, each on a new line, including the localhost (as localhost or as it's external name).
