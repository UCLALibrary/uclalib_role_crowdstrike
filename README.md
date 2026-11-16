CrowdStrike Falcon
==================

Installs and Enables CrowdStrike Falcon from a pre-existing DNF repository.
Will optionally configure CID, Cloud, and Provisioning Token.

Role Variables
--------------

- `crowdstrike_cid` (Optional)
- `crowdstrike_cloud` (Optional)
- `crowdstrike_provisioning_token` (Optional)
- `crowdstrike_force_update` (Default false)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: servers
      roles:
         - role: uclalib.crowdstrike
           vars:
             crowdstrke_cloud: 'us-2'
```

License
-------

BSD 3 Clause

Author Information
------------------

John H. Robinson, IV <jhriv@ucla.edu>
Powell Library, UCLA
