# nim-multicloud-failover-inference
A dual-cloud NVIDIA NIM deployment that serves GPU-accelerated LLM inference on GKE and AWS EKS, provisioned with Terraform, managed by Helm, autoscaled with KEDA, and fronted by a global HTTPS load balancer for seamless fail-over between Google Cloud and AWS.
