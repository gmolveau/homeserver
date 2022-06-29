# homeserver

- copy `hosts.ini.example` to `hosts.ini` and edit the variables
- run :

```bash
ansible-playbook -i hosts.ini --ask-become-pass playbook.yml
```

## TODO

- use ansible roles
