<p>
This script I made is for my own purpose, so I can save time and be more efficient when I need to install a Kubernetes cluster.
For now, this script only supports provisioning Kubernetes V1.29 and is supported only on Ubuntu 
server (tested on Ubuntu 22.04).

So, if you want to try installing the same Kubernetes version and use an Ubuntu server, feel free to use it. :metal:
</p>

<br/>
<br/>

📌 <b>Update :</b> 
- [x] Join Installation & Uninstallation Script in one script only.
- [x] Adding flag for options. 
- [x] Adding function for provision Worker Node.
- [x] Adding function for drain and delete specific worker node.
- [ ] Add file config for change subnet separated, so there's no need to change manually in main code.
- [x] Adding function for kubeadm init based on environment ( local vm or cloud )
    - [x] GCP cloud
- [ ] Adding function for install other kubernetes version dynamically
- [ ] Adding dynamic input subnet for kubeadm init and calico custom-resources.yaml
- [ ] Add more Linux OS Support :
    - [x] Ubuntu
    - [x] Debian
    - [ ] Centos
- [x] Support Kubernetes v1.32

<br/>
<br/>

> [!NOTE]
Please change the subnet in the global variables manually, according to your subnet.
