# Scalability
    Non functional Requirement: Scalability
    
    Problem : 
        Application goes unresponsive when increase in load due to insufficient resources like CPU, Storgae and Network bandwidth.
    Solution : 
        Provision the resources manually by adding more resources to application or deploy another instance of the application/server.
## Scalability
    
## Types of Scaling



## Kubernetes
Horizontal scaling means that the response to increased load is to deploy more Pods. 
This is different from vertical scaling, which for Kubernetes would mean assigning more resources (for example: memory or CPU) 
to the Pods that are already running for the workload.

The HPA can ensure that the cluster has enough replicas of the pod to handle the workload,
while the VPA can ensure that each pod has the necessary resources to perform its tasks efficiently.

## References

https://www.fullstaq.com/knowledge-hub/blogs/autoscaling-in-kubernetes

https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/

https://docs.aws.amazon.com/eks/latest/userguide/autoscaling.html

https://keda.sh/