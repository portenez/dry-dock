# Manual Config
Unfortunately, I haven't yet automated (even tried) the configuration of the provisioned
services. For now, here's the list of things to do:

## Archiva
- Create user **root/admin** (I'm using admin/password123)
- Create user **publisher** (publisher/password123). Set it as global repository observer and manager. 

## Gitlab
- Default user name password is: **root/5iveL!fe**. Login, and change password. I usually change it to (**password123**)
- Generate deploy ssh key (for read-only access).  [dry-dock_rsa.pub](dry-dock_rsa.pub) (public) included in this repo. 

## Jenkins

- Add git plugin
- Configure ssh credentials you can use included key-pair: dry-dock_rsa (private), and dry-dock_rsa.pub (public). The passphrase is password123
