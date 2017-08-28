# Dockeo


# Commande

## Build command
```
ansible-playbook run.ansible.yml -e stage=build
```

## Start command
```
ansible-playbook run.ansible.yml -e stage=start
```

## Stop command
```
ansible-playbook run.ansible.yml -e stage=stop
```

URL : 
- http://traefik.127.0.0.1.nip.io/
- http://symfony.127.0.0.1.nip.io/
- http://rabbitmq.127.0.0.1.nip.io/
- http://elasticsearch.127.0.0.1.nip.io/