# Vagrant CentOS Stream 9

This Vagrant configuration sets up a virtual machine using CentOS Stream 9 as the guest operating system and provisions it with httpd Server and other utilities. It also deploys a basic web page template to the Apache web server.

## Prerequisites

Before using this Vagrant setup, ensure you have Vagrant and VirtualBox (or your preferred provider) installed on your system.

### Installing Vagrant

1. **Download Vagrant:** Visit the [Vagrant Downloads Page](https://www.vagrantup.com/downloads.html) and download the installer for your operating system.

2. **Install Vagrant:** Follow the installation instructions for your platform to install Vagrant.

### Installing VirtualBox (or Alternative Provider)

If you don't have a virtualization provider already installed, Vagrant typically uses VirtualBox as the default provider. You can download VirtualBox from the [VirtualBox Downloads Page](https://www.virtualbox.org/wiki/Downloads) and install it on your system.

### installing Vagrant Box

1. **Choose a CentOS box from [Vagrant Cloud](https://app.vagrantup.com/boxes/search).**
2. **Create a new directory for your project**
3. **Navigate to the project directory.**
4. **Run vagrant init *name_of_box***

## Getting Started

1. **Clone this repository to your local machine.**
2. **Navigate to the project directory.**
3. **Run `vagrant up` to start the virtual machine.**
4. **Access the web server at [http://192.168.56.22](http://192.168.56.22).**

## Configuration

- Guest OS: CentOS Stream 9
- Private Network IP: 192.168.56.22
- Provisioning includes Apache HTTP Server installation and web page deployment.
- Customize the `Vagrantfile` as needed.

## License

This project is licensed under the MIT License.
