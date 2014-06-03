Vagrant with Ansbile provision for Juju local using lxc
==================

This is a work in progress intended to grow as a bounch of Ansible roles which will be extended to build your Juju environments.

Add new environments into the /group_vars/all

# Known issues
- When removing an environment from the file, is causing the lost of the configuration.
- Changing the order, is dangerous because the order is attach to the defined ports, so don't change the order!
