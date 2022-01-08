# Init for base VM with Ansible

Roles provisioned:
 * wahlax.ssh_config

Additional Task:
 * update CA certs

## Testing

Credit: Tested with vagrant image from [@geerlingguy's Ansible for Devops](https://github.com/geerlingguy/ansible-for-devops)

Run the following from the test directory:

### Initial Install
```
vagrant up
```

### Reapply provisioning
```
vagrant provision
```

