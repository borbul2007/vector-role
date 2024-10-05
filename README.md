ansible-vector
=========

Simple Vector deploy and management role.


Role Variables
--------------

You can change Vector version

```yaml
vector_version: "0.41.1"
```

Configure
--------

Refer the file templates/vector.toml.j2 to change the default values for Vector.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: vector_host 
      roles:
         - { }

License
-------

BSD

Author Information
------------------

Boris
