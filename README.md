# Fault-Tolerance-and-Availability-
Fault Tolerance  Fault tolerance is the system’s ability to continue operating correctly even when components fail.
In this project, fault tolerance can be achieved by:

Redundancy: Deploying multiple instances of critical services so a single instance can fail without disrupting operations.

Graceful Degradation: Designing features so that if one part fails, essential functions remain available.

Monitoring & Recovery: Using health checks and automated restarts (e.g., container orchestration like Kubernetes) to detect and recover from failures quickly.

 # Availability

Availability measures the percentage of time the system remains usable and responsive.
To maximize availability, this repository encourages:

High-Availability Architecture: Load balancing and distributed deployments across regions or zones.

Automated Scaling: Adjusting resources based on traffic to prevent outages.

Resilient Dependencies: Timeout, retry, and circuit-breaker patterns to handle external service issues gracefully.
