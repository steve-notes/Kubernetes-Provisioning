# Kubernetes Provisioning
### Kubernetes Installation Script using Kubeadm &amp; Calico Operator.  

For now, this script can only support to provision the kubernetes V1.29
and only support on ubuntu server ( tested on ubuntu 22.04 )

<br/>
<br/>

📌 <b>ToDo for Next Update :</b> 
- [x] Join Installation & Uninstallation Script in one script only
- [x] Adding flag for install or uninstall
- [x] Adding function for provision Worker Node
- [x] Adding flag for provision Worker Node
- [ ] Adding flag for kubeadm init based on environment ( local vm or cloud )
- [ ] Adding flag for install kubernetes version
- [ ] Adding dynamic input subnet for kubeadm init and calico custom-resources.yaml
- [ ] Add more Linux OS Support :
    - [x] Ubuntu
    - [ ] Centos

<br/>
<br/>

> [!NOTE]
Please change the subnet in the global variables manually, according to your subnet.
