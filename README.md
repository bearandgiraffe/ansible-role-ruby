Ruby
=========

A role to install ruby using chruby.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values:

```yml
ruby_ruby_version:            ruby-2.3.1
ruby_outdated_ruby_versions:  []

ruby_chruby_version:          0.3.9
ruby_chruby_version:          7220a96e355b8a613929881c091ca85ec809153988d7d691299e0a16806b42fd
ruby_chruby_exec_command:     chruby-exec

ruby_ruby_install_version:    0.6.0
ruby_ruby_install_checksum:   3cc90846ca972d88b601789af2ad9ed0a496447a13cb986a3d74a4de062af37d
ruby_ruby_install_command:    ruby-install
```

Dependencies
------------

None.

Example Playbook
----------------

```yml
- hosts: web
  roles:
     - { role: bearandgiraffe.ruby, ruby_ruby_version: ruby-2.3.1 }
```

License
-------

The Unlicense (see LICENSE)

Author Information
------------------

Youssef Chaker (@ychaker) from Bear & Giraffe LLC (@bearandgiraffe).
