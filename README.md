# openshift-base

## Single Node Openshift with ACS/AI
Note: Builds on a KVM Host and uses a Bastion/Support, Bootstrap and Control/SNO VM

```
<network>  
  <name>openshift4</name>  
  <forward mode='nat'>  
    <nat>  
      <port start='1024' end='65535'/>  
    </nat>  
  </forward>  
  <bridge name='openshift4' stp='on' delay='0'/>  
  <domain name='openshift4'/>  
  <ip address='192.168.100.1' netmask='255.255.255.0'>  
  </ip>  
</network>  
```

## References
https://computingforgeeks.com/how-to-install-kvm-on-rhel-8/
https://computingforgeeks.com/how-to-deploy-openshift-container-platform-on-kvm/
