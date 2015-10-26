# mvmc-sop

This project includes exploitation and deployment scripts for the [mvmc projet](https://github.com/ricofehr/mvmc).

Available commands:
* listtag: list the tags for mvmc project
* updatenodes: launch puppet agent interactively on the remote nodes
* pullmvmc: make a git pull on the remote prod mvmc management node
* rakemigrate: execute ruby on rails migration on the rest api
* rebuildember: rebuild the application.js for the ember webui
* restartpuma: restart the rails web server
* restartgitlab: restart gitlab services
* restartnginx: restart nginx, the revers-proxy of mvmc
* restartovpn: restart openvpn service
* rebootcontroller: reboot the controller node
* rebootneutron: reboot neutron node
* rebootglance: reboot glance node
* rebootcompute: reboot compute nodes
* rebootmvmc: restart services into mvmc manager node
* restartcontroller: restart all controller services (keystone, horizon, api, ...) 
* restartneutron: restart all neutron services
* restartglance: restart glance services
* restartcompute: restart all compute services
* restartmvmc: restart all mvmc manager node services
* deploycli: make and deploy a package for the mvmc cli command
* backupmvmc: make and retrieve a backup of mvmc project (rest api, assets and database)
* listbackupmvmc: list backup archives
* listbackuppuppet: list puppetmaster archives
* listbackupgitlab: list gitlab archives
* yardoc: generate documentation for the rest api
