## Creates a git hub repo
#### Requires a template repo to be created.

```
- name: validate if repo exists
- name: validate github if repo owner is member of {{ organization_name }}
- name: Create repo
- name: Assign an admin access to the owner of the repo
- name: Include extras on the repos
- name: Set default branch policy
```
```
extras:
- name: set repo to internal
- name: Add default collaborators
- name: Add the initial VERSION file
- name: Add a webhook to use ephemeral runner
```
