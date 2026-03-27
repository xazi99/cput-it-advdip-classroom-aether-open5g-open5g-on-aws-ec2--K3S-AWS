### 01-aws-ec2-instances-running.png
## AWS EC2 Instances Running
This screenshot shows the AWS EC2 instances used to deploy the k3s cluster, with all instances in a running state and passing health checks, confirming that the required cloud infrastructure was successfully provisioned.

### 02-k3s-master1-install-success.png
## k3s Installation Successful on Control Plane
This screenshot shows the k3s service running successfully on the primary control‑plane node (k3s-master-1), confirming that Kubernetes was installed and the control plane started correctly.

### 03-kubectl-get-nodes-wide.png
## Kubernetes Control‑Plane Nodes Ready
This screenshot displays the output of kubectl get nodes -o wide, showing the control‑plane nodes in a Ready state, confirming that the Kubernetes cluster is operational and the control plane is healthy.


### 04-kubectl-get-pods-all.png
## Kubernetes System Pods Running
This screenshot shows the output of kubectl get pods -A, confirming that core Kubernetes system pods are running across all namespaces, which demonstrates cluster health and successful service initialization.

### 04-k3s-master2-join-success.png (supporting evidence)
## Additional Control‑Plane Node Joined Successfully
This screenshot shows the k3s service running on a second control‑plane node (k3s-master-2), providing additional evidence of a multi‑node, high‑availability Kubernetes control plane.












# Evidence of Deployment
This section provides visual evidence of the successful deployment of a k3s Kubernetes cluster on AWS, including infrastructure provisioning, cluster formation, and system health verification.

# Cluster Nodes (kubectl get nodes)
The screenshot below shows the Kubernetes cluster nodes in a Ready state. It confirms that the k3s control plane and the agent node successfully joined the cluster.
#Get node.png

# System Pods (kubectl get pods -A)
The following screenshot displays Kubernetes system pods running across all namespaces.This confirms that core Kubernetes components such as DNS, ingress, and metrics services are operational.
#Get pods.png

# AWS EC2 Instances
The following screenshot shows the AWS EC2 instances used for the k3s deployment.
Both the control plane and agent node are running, confirming that the required cloud infrastructure was successfully provisioned.
#EC2 instances.png

# k3s Agent Installation Output
The screenshot below shows the successful installation of the k3s agent node.
The output confirms that the agent service was installed, enabled, and started using systemd.
#Terminal Output.png


