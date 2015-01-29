# Kusare-bento


This repositry is based on [chef/bento](https://github.com/chef/bento).

Created to testing on expired distribution.

## bentos

- Ubuntu 10.10(maverick)
    - Set default repository to `old-releases.ubuntu.com`.
- Ubuntu 11.04(natty)
    - Set default repository to `old-releases.ubuntu.com`.

## Usage

I have tested virtualbox-iso only.

```
$ cd packer
$ packer build -only=virtualbox-iso ubuntu-10.10-amd64.json
$ packer build -only=virtualbox-iso ubuntu-11.04-amd64.json
````

