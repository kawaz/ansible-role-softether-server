kawaz.AdobeMediaServer
=========

Install SoftEtherVPN Server.


Requirements
------------


Role Variables
--------------

| Name       | Default                    |  |
|------------|----------------------------|--|
| se_prefix  | /usr/local                 | The directory of SoftEtherVPN to install |
| se_version | v4.10-9473-beta-2014.07.12 | The version of SoftEtherVPN to install   |
| se_lang    | en                         | language setting. en|en|cn               |


Dependencies
------------

  
Example Playbook
----------------

```yaml:
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
