Installs and configures OpenVPN
=====================

This role requires Ansible 2.0.0.2 or higher.

Variables
--------------

| Name                          | Default                                                       | Description                                                                                            |
|:------------------------------|:--------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------|
| vars_files_distribution            | Ubuntu                                                       | Version of distrib   
| vars_files_distribution_release           | xenial                                                       | Version of release  

Role Variables
--------------

| Name                          | Default                                                       | Description                                                                                            |
|:------------------------------|:--------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------|
| vpnclient_config_path         | /etc/openvpn/config.conf                                                       | Path to configuration files  
| vpnclient_server.address            | ru2.freeopenvpn.org                                                       | VPN server address  
| vpnclient_server.port            | 12595                                                       | VPN server port 
| vpnclient_version            | openvpn=2.3.10-1ubuntu2.1                                                       | VPN version 

Role Variables for setting the certificate and keys
--------------

**vpnclient_ca** # ca in config.conf

Default:

