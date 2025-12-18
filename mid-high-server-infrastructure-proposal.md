# Server Infrastructure Proposal

## Overview
This proposal outlines a high-availability server infrastructure designed for a Laravel application using a **Load Balancer**, **Laravel Forge**, multiple **Application Servers**, and a dedicated **Database Server**.

The architecture ensures performance, scalability, and reliability.

---

## Infrastructure Architecture

- 1 × Load Balancer Server
- 2 × Application Servers (Laravel + Forge)
- 1 × Dedicated Database Server
- Daily Backups (20% of hosting cost)
- Laravel Forge (Standard Plan)

---

## Server Specifications & Pricing (USD)

### Load Balancer Server
**Plan:** CCX13  
- 2 vCPU  
- 8 GB RAM  
- 80 GB SSD  
- 20 TB Traffic  

**Price:**  
- **$14.03 / month**

---

### Application Servers (x2)
**Plan:** CCX33  
- 8 vCPU (AMD)  
- 32 GB RAM  
- 240 GB SSD  
- 30 TB Traffic  

**Price per server:**  
- **$56.15 / month**

**Total for 2 servers:**  
- **$112.30 / month**

---

### Database Server
**Plan:** CCX23  
- 4 vCPU  
- 16 GB RAM  
- 160 GB SSD  
- 20 TB Traffic  

**Price:**  
- **$28.07 / month**

---

## Hosting Cost Summary (Monthly)

| Component | Monthly Cost (USD) |
|---------|--------------------|
| Load Balancer | $14.03 |
| Application Servers (2×) | $112.30 |
| Database Server | $28.07 |
| **Total Hosting Cost** | **$154.40** |

---

## Backup Cost
Backup service is calculated as **20% of the total hosting cost**.

- **Monthly Backup Cost:**  
  **20% × $154.40 = $30.88**

---

## Laravel Forge
**Plan:** Standard  
- Used on Application Servers only  

**Cost:**  
- **$19.00 / month**

---

## Total Cost Breakdown

### Monthly Cost

| Item | Cost (USD) |
|-----|------------|
| Hosting | $154.40 |
| Backups (20%) | $30.88 |
| Laravel Forge | $19.00 |
| **Total Monthly Cost** | **$204.28** |

---

### Yearly Cost

| Item | Cost (USD / Year) |
|-----|------------------|
| Total Monthly × 12 | **$2,451.36** |

---

## Key Benefits
- High Availability using Load Balancer
- Scalable Laravel Infrastructure
- Dedicated Database Server
- Automated Daily Backups
- Easy Deployment & Management with Laravel Forge
- Optimized for Medium to High Traffic Applications

---

## Notes
- All prices are in USD.
- Costs are estimates and may vary slightly.
- Infrastructure can be scaled up or down based on project requirements.

---

## Contact Information
**Company Name:**  
**Email:**  
**Phone / WhatsApp:**  
**Website:**  
