이 역할은 **Dovecot (IMAP/POP3)** 메일 서버를 설치하고 구성합니다.

## Example Playbook
```yaml
- hosts: mail
  roles:
    - dovecot
