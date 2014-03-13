# Forge Users

Role that creates users on a node, and downloads particular SSH key for the user.

It takes she ssh keys from this repo: `https://git.forgeservicelab.fi/forge/ssh_keys/`

## Usage

```
  roles:
    - role: forge_users
      forge_users_private_token: "{{ gitlab_private_token }}"
      forge_users_list:
        - jrodrigu
        - ikoutone

```

The forge_users_private_token is a string authenticating to gitlab, which you can get in https://git.forgeservicelab.fi/profile/account. Use private token of the "keyreader" account.

