sbog/rainloop
=============

Role to install and configure Rainloop

#### Requirements

Ansible 2.4

#### Role Variables

```yaml
mail_hostname: mail.example.com
```

#### Dependencies

None

#### Example Playbook

```yaml
- name: Install and configure Rainloop
  hosts: localhost
  remote_user: root
  roles:
    - rainloop
```

#### License

Apache 2.0

#### Author Information

Stanislaw Bogatkin (https://sbog.ru)
