To Setup K8 Cluster of Instances Created:-


Connect to the AWS Instances through SSH (Public IP) and Key pair generated (Use MobaXterm)


Then Run the kubernetes.sh script 

then run 


```bash
sudo kubeadm init --pod-network-cidr=10.244.0.0/16
```


This will initiate kubernetes cluster and generate token for slave nodes to join the K8 cluster


![kubernetes-cluster-token](https://github.com/user-attachments/assets/767b496f-218b-43a7-8fa5-21bf85d77b26)
