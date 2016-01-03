# nextdeploy-sop

This project includes exploitation and deployment scripts for the [nextdeploy projet](https://github.com/ricofehr/nextdeploy).

Available commands:
* listtag: list the tags for nextdeploy project
* updatenodes: launch puppet agent interactively on the remote nodes
* pullnextdeploy: make a git pull on the remote prod nextdeploy management node
* rakemigrate: execute ruby on rails migration on the rest api
* rebuildember: rebuild the application.js for the ember webui
* restartpuma: restart the rails web server
* restartgitlab: restart gitlab services
* restartnginx: restart nginx, the revers-proxy of nextdeploy
* restartovpn: restart openvpn service
* rebootcontroller: reboot the controller node
* rebootneutron: reboot neutron node
* rebootglance: reboot glance node
* rebootcompute: reboot compute nodes
* rebootnextdeploy: restart services into nextdeploy manager node
* restartcontroller: restart all controller services (keystone, horizon, api, ...)
* restartneutron: restart all neutron services
* restartglance: restart glance services
* restartcompute: restart all compute services
* restartnextdeploy: restart all nextdeploy manager node services
* deploycli: make and deploy a package for the nextdeploy cli command
* backupnextdeploy: make and retrieve a backup of nextdeploy project (rest api, assets and database)
* listbackupnextdeploy: list backup archives
* listbackuppuppet: list puppetmaster archives
* listbackupgitlab: list gitlab archives
* yardoc: generate documentation for the rest api
