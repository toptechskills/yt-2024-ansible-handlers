# Code for Ansible YouTube video: Ansible Handlers Tutorial - How to Use Handlers in Your Roles and Playbooks

[Video on YouTube](https://youtu.be/rl8S5QoGvlM). In the video I show how you how you can use handlers in your playbooks and roles, as well as a rapid-fire deep dive of common handler questions and gotchas.

Update the `Vagrantfile` to point at your SSH public key:

```
# Vagrantfile
...
# Change this to your SSH public key path
PUBLIC_KEY_PATH = "...".freeze
```

Spin up the Vagrant VMs (ARM VMs in this video, check out free dev env lesson of [Productive with Ansible course](https://learn.toptechskills.com/courses/productive-with-ansible) to see non-ARM setup):

```
vagrant up
```

Run the playbooks:

```
# Handlers in playbook demo
ansible-playbook playbook.yml

# Handlers in role demo
ansible-playbook playbook_roles.yml
```
