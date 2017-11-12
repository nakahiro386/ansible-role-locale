Role Name
=========

nakahiro386.locale

Configure system locale.

Requirements
------------

* EL
  * None.
* Ubuntu
  * `python-apt`

Role Variables
--------------

```yaml
# defaults file for nakahiro386.locale
nakahiro386_locale: "ja_JP.UTF-8"
```

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: nakahiro386.locale
      become: yes
```

License
-------

MIT

