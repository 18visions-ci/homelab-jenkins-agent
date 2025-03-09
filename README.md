# homelab-jenkins-agent

Ansible playbooks and roles to deploy a Jenkins agent on Ubuntu 22.04.

## Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/homelab-jenkins-agent.git
    cd homelab-jenkins-agent
    ```

2. Run the playbook:
    ```sh
    ansible-playbook -i your_inventory_file main.yaml
    ```

## Requirements

- Ansible 2.9+
- Ubuntu 22.04 target hosts

## Roles

- `common`: Installs dependencies.
- `jenkins_agent`: Sets up Jenkins agent.

## License

MIT License.