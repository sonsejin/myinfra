이 역할은 **FTP 서버(vsftpd)** 를 설치하고 구성합니다.

## Requirements
- CentOS / RHEL 9 계열
- Ansible 2.9 이상

## Example Playbook
```yaml
- hosts: ftp
  roles:
    - myftp
