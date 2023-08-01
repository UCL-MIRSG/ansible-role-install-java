Ansible Role: mirsg.java
=========

A role for install and configuring Java.

Role Variables
--------------

`java` - A dictionary containing:

`profile_d`: Defaults to "/etc/profile.d".

`home`: Defaults to "/usr/lib/jvm/jre"

`package`: Defaults to "java-1.8.0-openjdk-devel"

`keystore_path`: Defaults to "/usr/lib/jvm/jre/lib/security/cacerts/"

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
      - { role: mirsg.java }
```

License
-------

BSD

Author Information
------------------

This role was created by the [Medical Imaging Research Software
Group](https://www.ucl.ac.uk/advanced-research-computing/expertise/research-software-development/medical-imaging-research-software-group)
at [UCL](https://www.ucl.ac.uk/).
