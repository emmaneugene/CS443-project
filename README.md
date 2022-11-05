# CVE-2022-0847: Dirty Pipe Vulnerability

## Team Members:

- Carmen Yip
- Cheyenne Jan Lee
- Chong Jie Mi
- Emmanuel Oh
- Lindy Lim

## Overview

A simple demonstration of the `CVE-2022-0847: Dirty Pipe` exploit that affected
Linux kernel versions above 5.8

The best way to run this would be on an x86 virtual machine or an old machine
without a kernel patch. Make sure that execution permissons are set on the 
`dirty-pipe` directory and `gcc` is installed, then run `compile.sh`

Alternatively, `setup.sh` does all of this for you 🙂

## Requirements

- `git` - For cloning this repository

- `gcc` - For compiling the source code