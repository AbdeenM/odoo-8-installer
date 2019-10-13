# Odoo V8 Installer

[![Status](https://travis-ci.org/AbdeenM/odoo-8.0-installer.svg?branch=master)](https://travis-ci.org/AbdeenM/odoo-8.0-installer)

A simple script to install [Odoo V8.0](https://www.odoo.com/) on your Linux server, download the script, run it and enjoy!

## Prerequisites

* Have a running linux server.
* Python v2 & 3.

## Installation

**Recommended: Update your system server before continuing, for Ubuntu run `sudo apt-get update` && `sudo apt-get upgrade`**

Moving Forward this assumes you have everything setup, to install the project either download the .zip file and extract or navigate to an empty directory and clone this repo:
```bash
git clone https://github.com/AbdeenM/odoo-8.0-installer.git
```
cd to the the extracted directory where `odoo-8.0-installer.sh` is located, then make the file executable by running:
```bash
chmod +x odoo-8.0-installer.sh
```
Start the installation process by running: `./odoo-8-installer.sh`

## Project Status

This script has not be tested with Odoo version > 8 so feel free to try it out or contribute!

## Contributing

Pull requests are welocme. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

## License

Released under the **[MIT License](http://mit-license.org/)**
