Add your host into `kong` group in your hosts file
```
ansible-playbook python_bootstrap.yml -i hosts
ansible-playbook site.yml -i hosts
```
When go to http://your.server:8080 for [dashboard](https://github.com/PGBI/kong-dashboard)