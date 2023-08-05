---
# the default layout is 'page'
icon: fas fa-gg-circle
order: 6
---

To compile and build an Arch, Debian, or RPM format package on a Linux architecture
for which a package is not provided, an appropriate development environment
must be installed.

On an Arch Linux based system:

```console
sudo pacman -S --needed base-devel
```

On a Debian based system:

```console
sudo apt update -y
sudo apt upgrade -y
sudo apt install build-essential coreutils git make tar zstd make
```

On an RPM based system:

```console
sudo dnf update
sudo dnf groupinstall "Development Tools" "Development Libraries"
```

Each platform may differ in package names, versions, and installation command.
It may require some iterations of this process to get all required development
packages installed.

Once you have an appropriate development environment setup, retrieve the
`Asciiville` source, compile the included utilities, and create an installation
package:

```console
git clone https://github.com/doctorfree/Asciiville
cd Asciiville
```

Run the command `./mkpkg` to create an installation package in
`./releases/<version>`.

A successful compilation and packaging will produce distribution/installation
files in `./releases/<version>/`.
