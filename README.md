# glusix
Zabbix Agent - Gluster

# Dependencies
## Packages
* ksh

### Debian/Ubuntu

    #~ sudo apt install ksh
    #~

### Red Hat
    #~ chmod -R 775 /etc/zabbix/scripts (phân quyền cho folder chứa glusxi)
    #~ sudo yum install ksh
    #~ yum install -y bc

# Deploy
## Zabbix

    #~ git clone https://github.com/sergiotocalini/glusix.git
    #~ sudo ./glusix/deploy_zabbix.sh
    #~ sudo systemctl restart zabbix-agent
    
*Note: the installation has to be executed on the zabbix agent host and you have to import the template on the zabbix web.*
