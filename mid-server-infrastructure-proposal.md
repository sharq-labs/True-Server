# Server Infrastructure Proposal

## Overview
High-availability Laravel infrastructure designed to host **multiple applications** with optimized cost while maintaining scalability and reliability.

---

## Infrastructure Architecture
- 1 × Load Balancer Server
- 2 × Application Servers (Laravel + Forge)
- 1 × Dedicated Database Server
- Daily Backups (20% of hosting cost)
- Laravel Forge ($19 / month)
- Primary IPv4 for each server

---

## Infrastructure Architecture Changes
- Load Balancer cost updated to **$7 / month**
- Application Servers reduced from **3 servers to 2 servers**

---

## Server Specifications & Individual Pricing (USD)

### 1️⃣ Load Balancer Server
**Purpose:**  
Traffic distribution, SSL termination, health checks.

**Cost**
- **Total:** **$7.00 / month**

---

### 2️⃣ Application Servers (x2)
**Purpose:**  
Hosting multiple Laravel applications, handling PHP requests, queues, and background jobs using Laravel Forge.

**Cost (per server)**
- **$58.05 / month**

**Total for 2 Application Servers**
- **$116.10 / month**

---

### 3️⃣ Database Server
**Purpose:**  
Dedicated database hosting for all applications to ensure performance, stability, and security.

**Cost**
- **Total:** **$29.97 / month**

---

## Hosting Cost Summary (Monthly)

| Component | Cost (USD) |
|---------|-----------|
| Load Balancer | $7.00 |
| Application Servers (2×) | $116.10 |
| Database Server | $29.97 |
| **Total Hosting Cost** | **$153.07** |

---

## Backup Cost
Backup service is calculated as **20% of total hosting cost**.

- Monthly Backup Cost:  
  **20% × $153.07 = $30.61**

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
| Hosting (Servers + IPv4) | $153.07 |
| Backups (20%) | $30.61 |
| Laravel Forge | $19.00 |
| **Total Monthly Cost** | **$202.68** |

---

### Yearly Cost
- **$2,432.16 / year**

---

## Key Benefits
- Designed to host multiple Laravel applications
- Cost-optimized high availability setup
- Load Balancer for traffic distribution
- Improved fault tolerance with 2 Application Servers
- Dedicated Database Server for performance and security
- Automated daily backups
- Centralized deployment and management via Laravel Forge

---

## Notes
- All prices are in USD
- One Primary IPv4 address is assigned to each server
- Infrastructure can be scaled horizontally by adding more Application Servers
