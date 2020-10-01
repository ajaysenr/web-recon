# Web-recon

This tool is created as a part of learning shell scripting, now I am making various changes to make it a better tool which can be used to collect various information of a website.
# Current features

  - Can collect subdomains of a website
  - Can collect CNAME record of the subdomains

### Dependencies

 - Install [Go Language](https://tzusec.com/how-to-install-golang-in-kali-linux/) in your system.
 - Install  [assetfinder](https://github.com/tomnomnom/assetfinder)

### Installation

```sh
$ git clone https://github.com/secretguard/web-recon.git
$ cd web-recon
$ ./install.sh
```


### Usage

```sh
$ ./web-recon.sh -h
$ ./web-recon.sh -d domain_name
```
