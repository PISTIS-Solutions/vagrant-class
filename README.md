# vagrant-class

# install the following tools
-  [Oracle virtual box](https://www.virtualbox.org/wiki/Downloads)
- [Haschicorp Vagrant](https://developer.hashicorp.com/vagrant/install)
- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

# Ensure you setup ssh agent on your local machne
- [SSH Agent for Windows](https://learn.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse?tabs=gui)
- [SSH Agent for Linux](https://ubuntu.com/server/docs/service-openssh)

**NOTE:** All windows command should be executed in Administrator mode

# useful commands
- `ssh-add -k <path-to-your-key>` add your ssh key to the ssh agent key chain
- `ssh-add -l` List all keys added to your ssh agent 
- `aws configure` configure aws cli credentials
- `vagrant plugin install vagrant-aws` install Vagrant aws plugin
       