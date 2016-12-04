# nodejs-env

Sets up environment for developing node-js applications

## Requirements

Ansible

## Configuration

Edit `nodejs-env.yml` according to your needs.

Specify nodejs version to be installed
```yaml
nodejs_version: "6.9.1"
```

Specify npm global packages
```yaml
nodejs_npm_global_packages: []
```

## Installation

```
ansible-playbook install-requirements.yml
ansible-playbook nodejs-env.yml
```

## License
[MIT](LICENSE)
