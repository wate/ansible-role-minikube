minikube
=================

Setup minikube(work in progress)

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `minikube_version`

インストールするバージョン

#### `minikube_packages`

インストールするパッケージ

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `minikube_dependency_packages`

#### `minikube_home`

#### `minikube_user`

#### `minikube_group`

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: minikube
```

License
--------------

Apache License 2.0
