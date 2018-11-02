# IGV server deployment

Mission: turn internal [IGV server](http://software.broadinstitute.org/software/igv/DataServer) installation [documentation](https://github.com/umccr/wiki/blob/master/bioinformatics/tools/igv/igv_server.md) into fully automated deployment recipe by using Ansible.

## How to operate this repository

Prerequisites:

	1. Have a working https://conda.io/miniconda.html installation.
	2. Install ansible inside a virtual environment, called "igv".
	3. Install [vagrant](https://www.vagrantup.com/).

Running the playbook:

```
vagrant up --provision
```
