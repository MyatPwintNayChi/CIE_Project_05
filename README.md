# Multi-Region Geolocation Routing Architecture with AWS Route 53 & Docker

This project demonstrates a highly available, multi-region web application deployment utilizing **AWS Route 53 Geolocation Routing**. Users are intelligently routed to the nearest regional stack (**Singapore** or **London**) based on their geographical location, ensuring minimal latency and optimized traffic management.

The microservices architecture consists of custom Docker containerized services (`dashboard-service` and `counting-service`) built, tagged, and pushed to Docker Hub, deployed inside isolated AWS VPCs, and secured with SSL/TLS certificates via AWS Certificate Manager (ACM).

---

## Architecture Overview

The system is deployed across two primary AWS Regions:
* **Singapore (`ap-southeast-1`)**
* **London (`eu-west-2`)**


