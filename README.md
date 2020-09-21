# Advanced Kubernetes Session syllabus

Textbook: https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks

Playlist: https://www.youtube.com/playlist?list=PLKFaWBYMOdDvE5tjP8qzcZOgAo7-ONhd8

## Day 1:
### Videos and Reading Material:
Azure Kubernetes Service Production Baseline: Intro - https://youtu.be/-Hjyqxn1cqI 

### Networking configuration:
Network topology:
-	Video: https://youtu.be/VN4L5eBjoCg
-	Reading: https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#network-topology  
                                                
### Plan the IP addresses:
-	Video: https://youtu.be/pgIKfOjz3co 
-	Reading: https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#plan-the-ip-addresses 
 
### Deploy Ingress resources:
-	Video: https://youtu.be/1qrLzsbUVvg 
-	Reading: https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#deploy-ingress-resources 

Note: You will only deploy the Ingress controller at a later step but the video and reading material will provide a foundation of how and why we are using them.

                        Secure Data Flow:
### Secure the network flow:
-	Video: https://youtu.be/9IE6weAOBqI 
-	Reading: https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#secure-the-network-flow 
                        
### Labs:
1. 🚀 Preparing for the cluster
https://github.com/mspnp/aks-secure-baseline#1-rocket-preparing-for-the-cluster

2. Build target network
https://github.com/mspnp/aks-secure-baseline/blob/main/04-networking.md

## Day 2:
### Videos and Reading Material:

### Cluster compute:
Compute for the base cluster (configure compute for the base cluster):
-	Video: https://youtu.be/NTJmaLpUHgw 
-	Reading: 
o	https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#configure-compute-for-the-base-cluster   
o	https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#use-infrastructure-as-code-iac
o	https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#workload-cicd
o	https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#cluster-cicd
                        Operations:
                        Cluster and workload CI/CD pipelines
-	Video: https://youtu.be/bL3lR8OzWrw 
-	Reading: https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#cluster-and-workload-operations-devops                               

### Identity Management:
Integrate Azure AD for the cluster and Integrate Azure AD for the workload
-	Video: https://youtu.be/nQHemp3Y1C8 
-	Reading: 
o	https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#integrate-azure-active-directory-for-the-cluster  
o	https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#integrate-azure-active-directory-for-the-workload 

### Secure Data Flow:
Add secret management:
-	Video: https://youtu.be/TC3vpq8l7CM 
-	Reading: 
o	https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#add-secret-management 

### Labs:
3. Deploying the cluster
https://github.com/mspnp/aks-secure-baseline#3-deploying-the-cluster

4. Deploy your workload
https://github.com/mspnp/aks-secure-baseline#4-deploy-your-workload

## Day 3:
### Videos and Reading Material:

### Operations:
Cluster health and metrics
-	Video: https://youtu.be/k-DDeAnuvFo 
-	Reading: 
o	https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#monitor-and-collect-metrics

                        Cost management and reporting:
-	Video: https://youtu.be/F6xhcLTQfe0 
-	Reading:
o	https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#cost-management 
 
### Business continuity:
Scalability:
-	Video: https://youtu.be/IAKAc6WomA0 
-	Reading: https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#node-and-pod-scalability 

### Cluster and node availability:
-	Video: https://youtu.be/h8XaKBeScoY 
-	Reading: https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#business-continuity-decisions 

### Availability and multi-region support:
-	Video: https://youtu.be/-gSBO_jZNXo 
-	Reading: https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks#availability-zones-and-multi-region-support 

### Labs:
5. 🏁 Validation
https://github.com/mspnp/aks-secure-baseline/blob/main/10-validation.md

Clean up resources
https://github.com/mspnp/aks-secure-baseline/blob/main/11-cleanup.md