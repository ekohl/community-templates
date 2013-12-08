# Templates

tested on:

* Ubuntu 10.04 (lucid)
* Ubuntu 12.04 (precise)
* Ubuntu 13.04 (raring)
* Debian 6 (Squeeze)
* Debian 7 (Wheezy)

# Host Parameters

The templates use some Host Parameters to contol the flow of the template. These are:

* install-disk: What device to install to (default: /dev/sda | /dev/vda)
* enable-puppetlabs-repo: Add the Puppet Labs APT repo to the APT sources during install (default: no)
