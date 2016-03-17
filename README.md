Grokking Vagrant and Ansible and VirtualBox
====

Some parts of this make sense, others are more obscure. For now, what's included here works.
My VirtualBox host is an Ubuntu 14.04 server. I used apt-get-install for VirtualBox and Ansible,
and installed Vagrant from a Debian package so I could get a fresher version than the official
Ubuntu version.

I'm a bit mystified by
[hosts](http://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ansible-on-ubuntu-14-04#configuring-ansible-hosts)
in Ansible. For now my solution is to use "all" since I'm currently only setting up one machine,
but I'll need to be smarter before too long.
