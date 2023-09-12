# Kubeflow 1.6 automated installation
To automate the installation of Kubeflow 1.6 using Ansible, you can create an Ansible playbook with the necessary tasks. Below is an outline of the Ansible playbook for automating the Kubeflow 1.6 installation

## Deployment Guide
Deploy ***kubeflow 1.6*** on kubernetes cluster using following command

* Dry run of kubeflow deployment

> **NOTE:** During a dry run, Kubeflow will not be deployed; instead, it will provide a preview of the resources that would be deployed.
```
    ansible-playbook -i inventory.yml kubeflow.yml --check --diff
```
* Deploy kubeflow
```
    ansible-playbook -i inventory.yml kubeflow.yml
```

# Default Username and Password:
user@example.com
12341234