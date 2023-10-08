# sre-oncall

# On-Call Prerequisites for HPC Clusters

Before beginning your on-call duties for our HPC clusters, ensure you've met all the prerequisites listed below. This will equip you with the necessary access and knowledge to handle issues effectively.

## General Prerequisites

1. **Training**: Ensure you've undergone on-call training and are familiar with the escalation procedure.
2. **Contact Information**: Update your contact information in the on-call rotation system.
3. **On-Call Tools**: Familiarize yourself with the tools used for alerts, communication, and ticketing.
4. **Backup Personnel**: Know who to contact for backup support, and ensure you have their up-to-date contact details.

# Important Contacts List

## Team

## InterCompany

## Vendors

# Per Cluster definitions

For each cluster, ensure you have:

## 1. Access:

- [ ] **IPMI/BMC Access**: Ensure you can access the Baseboard Management Controller or Integrated Platform Management Interface of each node.
- [ ] **SSH Access**: 
  - Admin-level SSH access to all cluster nodes.
  - Know the naming convention of nodes for easy identification.
  - Ensure you have the necessary SSH keys or authentication methods in place.
- [ ] **Management Console Access**: Access to any cluster-specific management consoles or GUIs.

## 2. Monitoring & Visualization:

- [ ] **Grafana Access**: 
  - Log in credentials to Grafana dashboards.
  - Familiarity with the layout of cluster-specific Grafana dashboards.
- [ ] **Alerting System**: Understand the alerting system, its thresholds, and know where to check logs.

## 3. Documentation:

- [ ] **Cluster Topology**: Familiarity with the cluster architecture, storage systems, networking, and any peculiarities.
- [ ] **Common Issues & Solutions**: Review documentation on known issues and their typical resolutions.

## 4. Software:

- [ ] **Scheduler**: Understand the job scheduler in use (e.g., Slurm, Torque) and basic commands.
- [ ] **Modules & Environment**: Know how to navigate software modules and environment setups on the cluster.

## 5. Safety Protocols:

- [ ] **Emergency Shutdown**: Know the procedure for safe emergency shutdowns if required.
- [ ] **Physical Access**: In case remote management fails, ensure you have the necessary permissions or contacts for physical access.
