# VMware
## Repoint VMware vCenter  (vCeter Linked)
```
cmsso-util domain-repoint -m pre-check --src-emb-admin administrator --replication-partner-fqdn vcsa-dc.vfoc.local --replication-partner-admin administrator --dest-domain-name vsphere.local
cmsso-util domain-repoint -m execute --src-emb-admin administrator --replication-partner-fqdn vcsa-dc.vfoc.local --replication-partner-admin administrator --dest-domain-name vsphere.local
```
