# Install Docker in Ubuntu, configure user, and download WordPress theme.

## Run playbook:

``` bash
ansible-playbook -i inv.ini playbook.yml
```

## Before launching the ```playbook.yml```, you need to make changes to the file ``inv.yml``: 
- Specify the ip address and host name. Also in the file ``vars.yml`` specify the directory for the theme and the user

### Перед запуском ```playbook.yml```, необходимо внести изменения в файле ```inv.yml```: 
- Указать ip-адрес и имя хоста. Также в файле ```vars.yml``` указать директорию для темы и пользователя 