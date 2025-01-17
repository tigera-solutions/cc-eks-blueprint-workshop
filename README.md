# EKS Blueprint Workshops with Calico Cloud: Hands-on EKS workshop </br>

## Welcome

In this EKS-focused workshop, you will work with AWS and Calico Cloud to learn how toutilize the observability plane of Calico Cloud to visualize traffic, help with troubleshooting connections and to implement zero-trust security for workloads to reduce the attack surface of applications running on EKS.  

In K8s, the network architecture is much flatter, and thus creates a challenge for the more traditional means of observing flows in the network. However the need for observability does not go away with kubernetes and remains a critical requirement for cluster-admins, devops and seurity teams to efficiently and effectively secure the kubernetes landscape. Any potential observability tool must understand the dynamic nature of K8s components and report data that is relevent and valuable to ensure the correct decisions are made when securing and debugging kubernetes clusters. Calico Cloud offers 3 observability tools, Service Graph, FlowViz and Kibana, that we will look at in more detail in this workshop along with network policies and using these tools to check and improve security by implementing a zero-trust policy model.

You will come away from this workshop with an understanding of how others in your industry are securing and observing cloud-native applications in AWS, along with best practices you can implement in your organization.

### Time Requirements

The estimated time to complete this workshop is 60-90 minutes.

### Target Audience

- Cloud Professionals
- DevSecOps Professional
- Site Reliability Engineers (SRE)
- Solutions Architects
- Anyone interested in Calico Cloud :)

## Modules

This workshop is organized in sequential modules. One module will build up on top of the previous module, so please, follow the order as proposed below.
 
Module 1 - [Getting Started](modules/module-1-getting-started.md)  
Module 2 - [Deploy an AWS EKS cluster](modules/module-2-deploy-eks.md)  
Module 3 - [Connect the AWS EKS cluster to Calico Cloud](modules/module-3-connect-calicocloud.md)  
Module 4 - [Observe traffic flows in Calico Cloud](modules/module-4-observe-traffic.md)  
Module 5 - [Secure pod traffic using Calico Policy Recommender](modules/module-5-secure-pod-traffic.md)  
Module 6 - [Zero-trust security for pod traffic](modules/module-6-zero-trust-security.md)</br>
Module 7 - [Use Observability to Troubleshoot Connectivity Issues](modules/module-7-troubleshooting.md)</br>
Module 8 - [Clean up](/modules/module-8-clean-up.md)  

--- 

### Useful links

- [Project Calico](https://www.tigera.io/project-calico/)
- [Calico Academy - Get Calico Certified!](https://academy.tigera.io/)
- [O’REILLY EBOOK: Kubernetes security and observability](https://www.tigera.io/lp/kubernetes-security-and-observability-ebook)
- [Calico Users - Slack](https://slack.projectcalico.org/)

**Follow us on social media**

- [LinkedIn](https://www.linkedin.com/company/tigera/)
- [Twitter](https://twitter.com/tigeraio)
- [YouTube](https://www.youtube.com/channel/UC8uN3yhpeBeerGNwDiQbcgw/)
- [Slack](https://calicousers.slack.com/)
- [Github](https://github.com/tigera-solutions/)
- [Discuss](https://discuss.projectcalico.tigera.io/)

> **Note**: The examples and sample code provided in this workshop are intended to be consumed as instructional content. These will help you understand how Calico Cloud can be configured to build a functional solution. These examples are not intended for use in production environments.
