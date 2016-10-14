# nextdeploy-sop

This project includes exploitation and deployment scripts for the [nextdeploy projet](https://github.com/ricofehr/nextdeploy).

Available commands:
* backupcontroller: backup openstack controller database
* bundleinstall: execute a "bundle install" into rest api folder
* backupnextdeploy: make and retrieve a backup of nextdeploy project
* checkcontroller: check openstack controller services
* checkneutron: check openstack neutron services
* checkglance: check openstack glance services
* checkcompute: check openstack compute services
* checknextdeploy: check nextdeploy node services
* cleanossec: clean nightly the vms traced by ossec
* deploycli: make and deploy a package for the nextdeploy cli command
* deployclitest: make and deploy a package for nightly build of the nextdeploy cli command
* gitlabreconfigure: execute a "gitlab-reconfigure" on gitlab webapp
* listbackupnextdeploy: list backup archives
* listbackuppuppet: list puppetmaster archives
* listbackupgitlab: list gitlab archives
* listtag: list the tags for nextdeploy project
* maintenanceui: put the webui in offline mode
* maintenanceapi: put the api in offline mode
* maintenancevms: put the vms in offline mode
* maintenanceoff: disable all offline mode
* puppetstart: enable puppet agents on openstack nodes, and nextdeploy node
* puppetstop: disable puppet agents on openstack nodes, and nextdeploy node
* updatenodes: launch puppet agent interactively on the remote nodes
* pullnextdeploy: make a git pull on the remote prod nextdeploy management node 
* rakemigrate: execute ruby on rails migration on the rest api
* rebuildember: rebuild the application.js for the ember webui
* rebootcontroller: reboot the controller node
* rebootneutron: reboot neutron node
* rebootglance: reboot glance node
* rebootcompute: reboot compute nodes
* rebootnextdeploy: restart services into nextdeploy manager node
* restartmemcached: restart memcached service for the webui
* restartpuma: restart the rails web server
* restartgitlab: restart gitlab services
* restartnginx: restart nginx, the revers-proxy of nextdeploy
* restartovpn: restart openvpn service
* restartcontroller: restart all controller services (keystone, horizon, api, ...)
* restartneutron: restart all neutron services
* restartglance: restart glance services
* restartcompute: restart all compute services
* restartnextdeploy: restart all nextdeploy manager node services
* yardoc: generate documentation for the rest api
