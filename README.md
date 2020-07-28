# Centos 7 Automated Practice Deployment

## Vagrant Commands to control the environment:
- `vagrant up` - Boots and provisions the environment
- `vagrant destroy -f` - Shuts down and destroys the environment
- `vagrant halt` - Only shuts down the environment VMs
- `vagrant suspend` - Puts the VMs in a suspended state
- `vagrant resume` - Takes VMs out of a suspended state

## Included systems:
- ipa.brydar.com
- repo.brydar.com
- system1.brydar.com
- system2.brydar.com

## System Details:
> repo
- IP - 192.168.1.
- Gateway - 192.168.1.1
- DNS - 192.168.1.1
> ipa
- 192.168.1.
- Gateway - 192.168.1.1
- DNS - 192.168.1.1
> system1
- 192.168.1.
- Gateway - 192.168.1.1
- DNS - 192.168.1.1
> system2
- 192.168.1.
- Gateway - 192.168.1.1
- DNS - 192.168.1.1

There is a repo available to use from `http://repo.brydar.com/rpms`

## Accessing the systems
Remember to add the IP addresses to your local host file if you want to connect to the guest systems with the hostname.
Username - vagrant
Password - vagrant

- For root - use `sudo` or `sudo su`
Access example - `ssh vagrant@192.168.55.21` or `vagrant ssh system`

## LDAP users
- Username = dave, lisa
- Password = password
