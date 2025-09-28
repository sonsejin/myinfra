이 역할은 **NTP 서버(chrony)** 를 설치하고 구성합니다.

## Example Playbook
```yaml
- hosts: ntp
  roles:
    - ntp
