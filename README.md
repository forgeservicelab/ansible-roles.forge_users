# Forge Users

Role that creates users on a node, and downloads particular SSH key for the user.

It takes she ssh keys from this repo: `https://git.forgeservicelab.fi/forge/ssh_keys/`

## Usage

```
roles:
  - role: forge_users
    forge_users_list:
      - tkarasek
      - jrodrigu
      - khappone

```

