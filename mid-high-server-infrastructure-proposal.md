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

## Server Pricing (USD)

### Load Balancer Server
- Monthly Cost: $14.03
- Primary IPv4: $1.90

---

### Application Servers (x3)
- Monthly Cost per server: $56.15
- Primary IPv4 per server: $1.90

---

### Database Server
- Monthly Cost: $28.07
- Primary IPv4: $1.90

---

## Hosting Cost Summary (Monthly)

| Component | Cost (USD) |
|---------|-----------|
| Servers | $210.55 |
| IPv4 Addresses (5 servers) | $9.50 |
| **Total Hosting** | **$220.05** |

---

## Backup Cost
Backup service is calculated as **20% of total hosting cost**.

- Monthly Backup Cost:  
  **20% × $220.05 = $44.01**

---

## Laravel Forge
- Cost: **$19.00 / month**

---

## Total Cost

### Monthly Cost

| Item | Cost (USD) |
|----|------------|
| Hosting + IPs | $220.05 |
| Backups (20%) | $44.01 |
| Laravel Forge | $19.00 |
| **Total Monthly Cost** | **$283.06** |

---

### Yearly Cost
- **$3,396.72 / year**

---

## Key Benefits
- Designed for multiple Laravel applications
- High Availability via Load Balancer
- Improved fault tolerance with 3 Application Servers
- Dedicated Database Server for performance & security
- Automated Daily Backups
- Centralized deployment using Laravel Forge

---

## Notes
- All prices are in USD
- One IPv4 address is assigned to each server
- Architecture can be scaled horizontally by adding more Application Servers
