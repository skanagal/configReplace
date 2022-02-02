# Config Replace

# Example run

```
root@64ca34851c2a:/myfiles/github-scripts/configReplace# ansible-playbook -i hosts configReplace.yml
Full dir path of config file in flash. Example- file1.cfg or work/file1.cfg: sko.cfg

PLAY [all] **********************************************************************************************************************************************

TASK [Replace config with the sko.cfg File] *************************************************************************************************************
ok: [172.30.154.63]
ok: [172.30.154.64]
ok: [172.30.154.65]
ok: [172.30.154.62]
ok: [172.30.154.192]
ok: [172.30.154.60]

PLAY RECAP **********************************************************************************************************************************************
172.30.154.192             : ok=1    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
172.30.154.60              : ok=1    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
172.30.154.62              : ok=1    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
172.30.154.63              : ok=1    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
172.30.154.64              : ok=1    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
172.30.154.65              : ok=1    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

```
