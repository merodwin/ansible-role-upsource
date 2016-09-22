ansible-role-upsource
=========

Installs Upsource from JetBrains

Requirements
------------


Role Variables
--------------
``` yaml
upsource_version: "3.0.4421"
download_directory: "/tmp/"
upsource_install_folder: "/opt/UpSource"
upsource_data_path: "{{upsource_install_folder}}/data"
upsource_user: "upsource"
upsource_group: "upsource"
upsource_http_port: "8080"
```

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

``` yaml
- hosts: upsource
  roles:
    - role: ansible-role-upsource
```
License
-------

BSD

Author Information
------------------

[merodwin](hhtps://www.github.com/merodwin)
