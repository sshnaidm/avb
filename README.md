# AVB

Ansible Virtual Baremetal for Openstack

Inspired by [OVB - Openstack Virtual Baremetal](https://opendev.org/openstack/openstack-virtual-baremetal) project.

## Howto

Configure your `clouds.yaml` for Openstack. Create your environment file from template `setup.yml`.
Run the playbook:

```bash
ansible playbook.yml -e @my_setup.yml
```

To remove environment, run:

```bash
ansible playbook.yml -e @my_setup.yml -e teardown=true
```
