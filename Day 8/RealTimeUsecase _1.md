RealTime Use Case 1 : Docker + Terraform Automation

✅ Step 1 — Dockerized a Custom Nginx App

Built using the lightweight nginx:alpine base image
Added a custom HTML page to display app information
Configured a HEALTHCHECK to monitor the container’s live status

✅ Step 2 — Automated Deployment with Terraform

Defined provider and resource blocks for Docker infrastructure
Executed terraform init, terraform plan, and terraform apply to provision via code
Achieved Infrastructure as Code (IaC) consistency and reusability

✅ Step 3 — Verified and Monitored Health

Ran docker ps to confirm the container’s status and uptime
Observed HEALTHCHECK results to ensure container stability
