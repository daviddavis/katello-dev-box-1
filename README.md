katello-dev-box
===============

This is a Vagrant project for setting up katello development environment inside a VM.

## Dependencies

Install Vagrant. See [the Vagrant downloads page](http://www.Vagrantup.com/downloads.html). Also, you'll need a VM provider like VirtualBox, libvirt, or VMWare Fusion.

## Usage

Clone this repository inside the same directory you have katello and foreman
in.

```
cd ~/Projects
git clone https://github.com/Katello/katello-dev-box.git
```

Then run vagrant up. By default this uses VirtualBox:

```
vagrant up
```

To use libvirt, run the following:

```
vagrant up --provider=libvirt
```