# Ansible_integration_jenkins

# Prerequisites:
    Ansible server should be installed
    Jenkins Server should be installed

# Integration Setps

1.Install "publish Over SSH"

      Manage Jenkins > Manage Plugins > Available > Publish over SSH
      
2.Enable connection between Ansible and Jenkins

      Manage Jenkins > Configure System > Publish Over SSH > SSH Servers

  SSH Servers:

        Hostname:<ServerIP>
        username: ansadm
        password: *******
  
Test the connection "Test Connection"
