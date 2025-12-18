# Server Infrastructure Proposal

## Overview
High-availability Laravel infrastructure designed to host **multiple applications** using a Load Balancer, Laravel Forge, multiple Application Servers, and a dedicated Database Server.

This setup ensures scalability, fault tolerance, and stable performance for production workloads.

---

## Infrastructure Architecture
- 1 × Load Balancer Server
- 3 × Application Servers (Laravel + Forge)
- 1 × Dedicated Database Server
- Daily Backups (20% of hosting cost)
- Laravel Forge ($19 / month)
- Primary IPv4 for each server

---

## Server Specifications & Individual Pricing (USD)

### 1️⃣ Load Balancer Server
**Purpose:**  
Traffic distribution, SSL termination, health checks.

**Specifications**
- CPU: 2 vCPU  
- RAM: 8 GB  
- Storage: 80 GB SSD  
- Traffic: 20 TB  

**Cost**
- Server: $14.03 / month  
- Primary IPv4: $1.90 / month  
- **Total:** **$15.93 / month**

---

### 2️⃣ Application Servers (x3)
**Purpose:**  
Hosting multiple Laravel applications, handling PHP requests, queues, and background jobs using Laravel Forge.

**Specifications (per server)**
- CPU: 8 vCPU (AMD)  
- RAM: 32 GB  
- Storage: 240 GB SSD  
- Traffic: 30 TB  

**Cost (per server)**
- Server: $56.15 / month  
- Primary IPv4: $1.90 / month  
- **Total per server:** **$58.05 / month**

**Total for 3 Application Servers**
- **$174.15 / month**

---

### 3️⃣ Database Server
**Purpose:**  
Dedicated database hosting for all applications to ensure performance, stability, and security.

**Specifications**
- CPU: 4 vCPU  
- RAM: 16 GB  
- Storage: 160 GB SSD  
- Traffic: 20 TB  

**Cost**
- Server: $28.07 / month  
- Primary IPv4: $1.90 / month  
- **Total:** **$29.97 / month**

---

## Hosting Cost Summary (Monthly)

| Component | Cost (USD) |
|---------|-----------|
| Load Balancer | $15.93 |
| Application Servers (3×) | $174.15 |
| Database Server | $29.97 |
| **Total Hosting Cost** | **$220.05** |

---

## Backup Cost
Backup service is calculated as **20% of total hosting cost**.

- Monthly Backup Cost:  
  **20% × $220.05 = $44.01**

---

## Laravel Forge
- Plan: Standard
- Used on Application Servers only
- **Cost:** **$19.00 / month**

---

## Total Cost Breakdown

### Monthly Cost

| Item | Cost (USD) |
|----|------------|
| Hosting (Servers + IPv4) | $220.05 |
| Backups (20%) | $44.01 |
| Laravel Forge | $19.00 |
| **Total Monthly Cost** | **$283.06** |

---

### Yearly Cost
- **$3,396.72 / year**

---

## Key Benefits
- Designed to host multiple Laravel applications
- High availability using Load Balancer
- Improved fault tolerance with 3 Application Servers
- Dedicated Database Server for performance and security
- Automated daily backups
- Centralized deployment and management via Laravel Forge

---

## Notes
- All prices are in USD
- One Primary IPv4 address is assigned to each server
- Infrastructure can be scaled horizontally by adding more Application Servers
