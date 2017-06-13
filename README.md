
# Ansible Roles for installing the Feedhenry Build-Farm-2


## Requirements

Ansible 2.2.0 or higher.


## Role Variables


## Example
```
- host: master
  roles:
  - {role: feedhenry.buildfarm-installer, tags: feedhenry-buildfarm}
```


## Adding changes to Ansible Galaxy

* Create an account on [Ansible Galaxy](https://galaxy.ansible.com/) using your github account

* Log in to ansible galaxy 

* Using username and password
```
ansible-galaxy login
```
Enter you username and password when prompted

* Using github token
```
ansible-galaxy login --github-token <github-token>
```

### Import a role to ansible-galaxy

Make the necessary changes and merge them to master. Update the package on Ansible Galaxy by running:

```
ansible-galaxy import github_user github_repo
```

## License

Apache 2.0
