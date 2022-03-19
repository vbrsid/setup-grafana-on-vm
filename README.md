# Setup Grafana

You can use this ansible script to setup Grafana on a VM.

## 1. Pre-requisites

1. 1 machines is available for Grafana setup (eg: 4 cores 8 gb)
2. ansible is setup on ansible-controller VM (different from the above 4 machines)
3. ssh keys are copied to the 1 machine so that it is accessible by ansible without password

## 2. Install Grafana using ansible

Change the IP addresses of the 1 machine in the 'hosts' file and then run the following:

```
ansible-playbook -i hosts install-grafana.yaml
```
