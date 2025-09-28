이 역할은 **DNS 서버(BIND)** 를 설치하고 구성합니다.

## Requirements
- CentOS / RHEL 9 계열
- Ansible 2.9 이상

## Role Variables
- 필요 시 `group_vars` 참고

## Dependencies
- 없음

## Example Playbook
```yaml
- hosts: dns
  roles:
    - mydns
