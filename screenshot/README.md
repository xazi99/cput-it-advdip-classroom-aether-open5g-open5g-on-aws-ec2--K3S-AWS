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


