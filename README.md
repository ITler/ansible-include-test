# About
This ansible role should demonstrate inconsistent (or at least unexpected difference in) behavior when using `include` command for tasks in Plays. This also applies to `include_role` command.

## Using role
Role can be executed, locally

    - hosts: localhost
      gather_facts: False

      roles:
        - { role: include-test }

## Hint
Use `--tags` to focus use cases. See code for available tags, i.e. `ansible-playbook --tags=fact ...`
