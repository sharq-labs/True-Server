# Server Infrastructure Proposal

## Overview
High-availability Laravel infrastructure using Load Balancer, Laravel Forge, multiple Application Servers, and a dedicated Database Server.

---

## Infrastructure Architecture
- 1 × Load Balancer Server
- 2 × Application Servers (Laravel + Forge)
- 1 × Database Server
- Daily Backups (20% of hosting cost)
- Laravel Forge ($19 / month)
- Primary IPv4 for each server

---

## Server Pricing (USD)

### Load Balancer Server
- Monthly Cost: $14.03
- Primary IPv4: $1.90

---

### Application Servers (x2)
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
| Servers | $154.40 |
| IPv4 Addresses | $7.60 |
| **Total Hosting** | **$162.00** |

---

## Backup Cost
- Backup = 20% of hosting
- Monthly Backup Cost: **$32.40**

---

## Laravel Forge
- Cost: **$19.00 / month**

---

## Total Cost

### Monthly
| Item | Cost |
|----|-----|
| Hosting + IPs | $162.00 |
| Backups | $32.40 |
| Laravel Forge | $19.00 |
| **Total Monthly** | **$213.40** |

### Yearly
- **$2,560.80 / year**

---

## Notes
- All prices are in USD
- One IPv4 address is assigned to each server
- Infrastructure is scalable based on demand
