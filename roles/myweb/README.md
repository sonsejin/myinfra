이 역할은 **WEB 서버(Apache)** 를 설치하고 구성합니다.

## Example Playbook
```yaml
- hosts: web
  roles:
    - myweb
