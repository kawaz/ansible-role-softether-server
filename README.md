kawaz.softether-server
=========

Install SoftEtherVPN Server.


Requirements
------------
Nothing

Role Variables
--------------

| Name       | Default                    |                                          |
|------------|----------------------------|------------------------------------------|
| se_prefix  | /usr/local                 | The directory of SoftEtherVPN to install. It is Installed to `{{se_prefix}}/vpnserver/`. |
| se_version | v4.10-9473-beta-2014.07.12 | The version of SoftEtherVPN to install   |
| se_lang    | en                         | The language setting. ja, en, cn               |


Dependencies
------------
Nothing

  
Example Playbook
----------------

```
- hosts: servers
  roles:
     - { role: kawaz.softether-server }
```

License
-------

MIT

Author Information
------------------

Yoshiaki Kawazu

https://twitter.com/kawaz
