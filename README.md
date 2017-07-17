Role Name
=========

nakahiro386.locale

Requirements
------------

* EL5, EL6
  * None.
* EL7
  * `localectl`

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

