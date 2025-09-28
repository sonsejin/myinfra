이 역할은 **DB 서버(MariaDB/MySQL)** 를 설치하고 구성합니다.

## Example Playbook
```yaml
- hosts: db
  roles:
    - mydb
