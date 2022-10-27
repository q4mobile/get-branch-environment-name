# get-environment-name

A GitHub Action to generates an environment name based on branch name.

## Usage

```yaml
- name: Get environment name
  uses: q4mobile/get-branch-environment-name@latest
  with:
    branch-name: PRDVOPS-XXX  # Jira project key
```
