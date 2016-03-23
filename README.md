## About

This helps to setup a Raspberry PI computer as a minimal download station. It will:

* run [transmission-daemon](https://www.transmissionbt.com/download/) available via rpc;
* connect to net shares for keeping downloaded files.

## Install

Put custom credentials into `passwords.yml` config:

    cp passwords.yml.sample passwords.yml
    vim passwords.yml

Customize role variables and set correct hosts in the inventory file `hosts`.

Run installation script:

    ./setup.sh

## Requirements

* Installed [ansible](http://docs.ansible.com/ansible/intro_installation.html) on the local machine.
* User named `pi` within Raspberry PI with passwordless ssh access and passwordless sudo.

## Supported target platforms

* Raspbian GNU/Linux 7 (wheezy)

## License

MIT License
