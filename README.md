# Ansible Infra Collection

이 Collection은 DNS, FTP, WEB, DB, MAIL, NTP 서버 구성을 위한 Ansible Roles 모음입니다.

## 포함된 Roles
- mydns
- myftp
- myweb
- mydb
- postfix
- dovecot
- ntp

## 실행 방법
```bash
ansible-playbook -i inventory playbooks/site.yml
