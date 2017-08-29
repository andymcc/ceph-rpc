## rpc-ceph
This is a ceph AIO(All in One) deployed using ceph-ansible.   

### Virtual Machine requirements
Rackspace Public Cloud
 * general-8
 * xenial

### To run
```
./scripts/bootstrap-ansible.sh
ansible-playbook -i tests/inventory tests/setup-ceph-aio.yml
```