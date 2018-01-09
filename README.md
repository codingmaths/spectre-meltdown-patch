
# Spectre-Meltdown Patch

* As we all know all Operating systems are affected with Spectre-Meltdown bug. Recently all major operating systems have released the latest patch for this.

* We can use this ansible role to apply the patch on all major Linux based operating systems.

* List of affected Linux distros

    1. Red Hat Enterprise Linux 5 (including clones such as CentOS/Oracle/Scientific Linux 5)
    2. Red Hat Enterprise Linux 6 (including clones such as CentOS/Oracle/Scientific Linux 6)
    3. Red Hat Enterprise Linux 7 (including clones such as CentOS/Oracle/Scientific Linux 7)
    4. Debian Linux wheezy
    5. Debian Linux jessie
    6. Debian Linux stretch
    7. Deiban Linux buster, sid
    8. SUSE Linux Enterprise 11
    9. SUSE Linux Enterprise 12
    10. OpenSuse Linux based upon SUSE 12/11
    11. Fedora Linux 26
    12. Fedora Linux 27
    13. Amazon Linux AMI (Bulletin ID: ALAS-2018-939)


### Requirement

* ansible 2.4.2.0 (pip install ansible)
* Python 2.7
* Slack Tocken for notification


## USAGE

### Install Ansible
Folowing command can be used to Install Ansible
```
$ pip install ansible
```

### Create a host file
Following example make ansible aware of the Host servers
```bash
$ vi ansible.host
```

### Run ansible Script
Below command can be used to run the ansible role
```
$ ansible-playbook -i hosts spectre-meltdown.yml --private-key=/key-path
```

### Developer

Email: sanjaym756@gmail.com
