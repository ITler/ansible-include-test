# About
This ansible role should demonstrate inconsistent (or at least unexpected difference in) behavior when using `include` command for tasks in Plays. This also applies to `include_role` command.

## Using role
Role can be executed, locally. See `test.yml`, which should be runnable, if you cloned this repository to directory named *include-test*.

    ansible-playbook test.yml

## Hint
Use `--tags` to focus use cases. See code for available tags, i.e.

    `ansible-playbook test.yml --tags=fact ...`
