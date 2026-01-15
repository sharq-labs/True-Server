# Server Infrastructure Proposal (Single Server)

## Overview
Single-server Laravel infrastructure designed to host one or multiple small-to-medium applications with optimized cost and simple management using Laravel Forge.

This setup is suitable for startups, MVPs, and low-to-medium traffic production environments.

---

## Infrastructure Architecture
- 1 × Application Server (Laravel + Database)
- Daily Backups (20% of hosting cost)
- Laravel Forge (Paid)
- Primary IPv4 for the server

---

## Server Specifications & Pricing (USD)

### 1️⃣ Application Server
**Purpose:**  
Hosting Laravel applications, running PHP, queues, background jobs, and database on the same server using Laravel Forge.

**Specifications**
- CPU: 8 vCPU (AMD)
- RAM: 32 GB
- Storage: 240 GB SSD
- Traffic: 30 TB

**Cost**
- Server: $56.15 / month  
- Primary IPv4: $1.90 / month  
- **Total:** **$58.05 / month**

---

## Hosting Cost Summary (Monthly)

| Component | Cost (USD) |
|---------|-----------|
| Application Server | $58.05 |
| **Total Hosting Cost** | **$58.05** |

---

## Backup Cost
Backup service is calculated as **20% of total hosting cost**.

- Monthly Backup Cost:  
  **20% × $58.05 = $11.61**

---

## Laravel Forge
- Plan: Standard (Already Paid)
- **Cost:** **$19.00 / month**

---

## Total Cost Breakdown

### Monthly Cost

| Item | Cost (USD) |
|----|------------|
| Hosting (Server + IPv4) | $58.05 |
| Backups (20%) | $11.61 |
| Laravel Forge | $19.00 |
| **Total Monthly Cost** | **$88.66** |

---

### Yearly Cost
- **$1,063.92 / year**

---

## Key Benefits
- Simple and cost-effective setup
- Suitable for MVPs and small-to-medium projects
- Laravel Forge for easy deployment and management
- Database and application on the same server
- Automated daily backups
- Easy to scale later to multi-server architecture

---

## Notes
- All prices are in USD
- One Primary IPv4 address is assigned to the server
- Can be upgraded later to Load Balancer + Multiple Application Servers if needed
