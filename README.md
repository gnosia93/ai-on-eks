# ai-on-eks

* provision eks cluster with 2 gpu nodes
* enable gpu for k8s
* [configure DCGM for workerload /w prometheus](https://aws.amazon.com/ko/blogs/mt/monitoring-gpu-workloads-on-amazon-eks-using-aws-managed-open-source-services/) 
The NVIDIA Data Center GPU Manager (DCGM) is a set of low overhead tools that can perform a variety of functions including active health monitoring, diagnostics, system validation, policies, power and clock management, group configuration, and accounting. DCGM includes APIs for gathering GPU telemetry. The NVIDIA GPU Operator which installs DCGM Exporter uses Go bindings to collect GPU telemetry data such as memory utilization, and traffic interconnect from DCGM and then exposes it to an http endpoint (/metrics) which is remote written and stored in Amazon Managed Service for Prometheus. The NVIDIA GPU Operator add-on uses the operator framework within Amazon EKS, to automate the management of all NVIDIA software components needed to provision GPU, including DCGM and DCGM Exporter.    
