# Ansble configuration for installing node and npm on a remote server, and deploying a Nodejs application on the server.

```
ansible linode -i hosts -m ping
```

```
ansible-playbook -i hosts sala-node-playbook.yml
```