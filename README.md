## About

This helps to setup a Raspberry PI computer as a minimal download station. It will:

* run [transmission-daemon](https://www.transmissionbt.com/download/) available via rpc;
* connect to net shares for keeping downloaded files.

## Install

Put custom credentials into `passwords.yml` config:

    cp passwords.yml.sample passwords.yml
    vim passwords.yml

Customize role variables.

Run installation script:

    ./setup.sh

## Requirements

* [ansible](http://docs.ansible.com/ansible/intro_installation.html)

## Supported target platforms

* Raspbian GNU/Linux 7 (wheezy)

## License

MIT License
