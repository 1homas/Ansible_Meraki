# Ansible with Meraki

Basic Ansible roles and playbooks for working with Cisco Meraki organizations, admins, networks, and devices.





## Quick Start

1. Clone this repository:  

    ```bash
    git clone https://github.com/1homas/Ansible_Meraki_Show 
    ```

1. Create your Python environment and install Ansible:  

    ```bash
    pip install --upgrade pip
    pip install pipenv
    pipenv install --python 3.9
    pipenv install ansible jmespath
    pipenv shell
    ```

    > 💡 If you have any problems installing Python or Ansible, see [Installing Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

2. Export your [Meraki Dashboard API key](https://documentation.meraki.com/General_Administration/Other_Topics/Cisco_Meraki_Dashboard_API) into your terminal environment:  

    ```bash
    export MERAKI_KEY='EXAMPLE+KEYc320e12ee407159487a4cabc41abb'
    ```

3. Edit the `show.yaml` file and change the variable `meraki_org_name` to match *your* organization. 

4. Run the Ansible playbook(s).  

    ```bash
    ansible-playbook show.yaml
    ```





## License

The examples in this repository are licensed under the [Cisco Sample Code License](https://developer.cisco.com/site/license/cisco-sample-code-license/).





## Resources

- [cisco.meraki](https://docs.ansible.com/ansible/latest/collections/cisco/meraki/index.html) Ansible Documentation




