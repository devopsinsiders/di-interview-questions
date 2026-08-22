
Q1. What about experience with Kubernetes within the cloud? Have you got any exposure with AKS?

Q2. Have you performed any cluster-level operations as well? Let's say upgrading from one version to another or doing some patching with a cluster. Have you managed all these operations?

Q3. Let's say I want to upgrade my cluster from one version to another, with zero downtime or with minimal downtime. How do you achieve that?

Q4. What will be the first step?

Q5. Your control plane should be upgraded, right?

Q6. In this case, there might be some downtime for the users. How do you avoid that?

Q7. How your workload will be distributed on the other node?

Q8. But it's not necessary, right? It's not necessary that I'm having multiple replicas for my application pod.

Q9. Then how do you take care of that? There is only one replica and only two pods or three pods are there.

Q10. Then how do you take care of that?

Q11. Have you done any cluster upgrades yourself, from your side?

Q12. How are you guys taking downtime for that? Or you do it? Like, how are you managing that?

Q13. Let's say you're having a five-node cluster, and I'm having my deployment with three replicas. I want to make sure that each of my replicas is on a different node, high availability within the cluster. Now, how will you achieve that?

Q14. How?

Q15. I want to make sure each of your replicas is scheduled on a different node. How do you do it?

Q16. How do you make sure that only one replica of the pod is getting scheduled on each node?

Q17. Let's consider there is a pod which is running in your node, and it is trying to utilize all the resources in your node. Currently your node is reaching its full capacity, and the critical pods are getting evicted from your node. First of all, how do you fix this problem? How do you make sure that all the resources do not get utilized from your node, and how do you make sure that your critical pods do not get evicted? They should be protected. How do you take care of this?

Q18. But how is your probe responsible for the resources? I'm talking about your pod trying to use a lot of resources from your node. How will your probe manage that?

Q19. How can you manage that within a pod?

Q20. How do you manage it? Currently, what's happening is my pod is trying to utilize all the resources on my node. I don't want that. How do you restrict your pod to that?

Q21. The second part which I was talking about is your critical pods are getting evicted from your node. How do you protect your critical pods? I don't want my critical pods to be getting evicted from my node.

Q22. How do pods communicate, let's say, within the same namespace or within multiple namespaces? How do pods communicate with each other?

Q23. So that's a service, right? ClusterIP service you are saying?

Q24. Can you explain me then why only we use ClusterIP? Why don't we use other services? Like, if only ClusterIP is sufficient, then why do we have NodePort, why do we have LoadBalancer, why do we have headless services?

Q25. Why can't we use NodePort for the internal communication?

Q26. Have you tried using NodePort for internal communication?

Q27. What about headless service? Are you aware of the concept of headless service within Kubernetes?

Q28. Let's make sure that there are two namespaces within my cluster. I want to make sure that these two namespaces or the pods within these two namespaces should not be able to communicate with each other. How can you achieve that?