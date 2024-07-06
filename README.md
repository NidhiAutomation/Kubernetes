# Kubernetes

1. Create a Kubernetes cluster by deploying a master node and 2 worker nodes.
2. Install Kubernetes on all the machines and initialize the Kubernetes control-plane node on master node.
3. Using kubeadm join setup nodes in the worker nodes.
4. Create a Deployement of 2 replicas with image as apache2, the pods would be created in the worked nodes distributed equally
5. Containerize a sample code and push it to Dockerhub.
6. Create a Deployement of 2 replicas with image that is pushed to docker in above step.
7. Using the above code deploy Ingress with below rules :
   - */apache* to be pointed to the apache pods.
   - */customImage* to be pointed to the GitHub application.
