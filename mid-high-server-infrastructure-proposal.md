# Server Infrastructure Proposal

## Overview
This proposal covers a high-availability server infrastructure designed for a Laravel application using **Load Balancer**, **Laravel Forge**, multiple **Application Servers**, and a dedicated **Database Server**.

The setup ensures scalability, performance, and reliability.

---

## Infrastructure Architecture

- 1 × Load Balancer Server
- 2 × Application Servers (Laravel + Forge)
- 1 × Dedicated Database Server
- Daily Backups (20% of hosting cost)
- Laravel Forge (Pro Plan)

---

## Server Specifications & Pricing

### Load Balancer Server
**Plan:** CCX13  
- 2 vCPU  
- 8 GB RAM  
- 80 GB SSD  
- 20 TB Traffic  

**Price:**  
- €11.99 / month  
- ≈ **$14.03 / month**

---

### Application Servers (x2)
**Plan:** CCX33  
- 8 vCPU (AMD)  
- 32 GB RAM  
- 240 GB SSD  
- 30 TB Traffic  

**Price per server:**  
- €47.99 / month  
- ≈ **$56.15 / month**

**Total for 2 servers:**  
- ≈ **$112.30 / month**

---

### Database Server
**Plan:** CCX23  
- 4 vCPU  
- 16 GB RAM  
- 160 GB SSD  
- 20 TB Traffic  

**Price:**  
- €23.99 / month  
- ≈ **$28.07 / month**

---

## Hosting Cost Summary (Monthly)

| Component | Monthly Cost (USD) |
|--------|--------------------|
| Load Balancer | $14.03 |
| Application Servers (2×) | $112.30 |
| Database Server | $28.07 |
| **Total Hosting** | **$154.40** |

---

## Backup Cost
Backup service is calculated as **20% of the hosting cost**.

- Monthly Backup Cost:  
  **20% × $154.40 = $30.88**

---

## Laravel Forge
**Plan:** Forge Pro  
- Unlimited servers  
- Used on Application Servers only  

**Cost:**  
- ≈ **$36 / month**

---

## Total Cost Breakdown

### Monthly Cost
| Item | Cost (USD) |
|----|------------|
| Hosting | $154.40 |
| Backups (20%) | $30.88 |
| Laravel Forge | $36.00 |
| **Total Monthly Cost** | **$221.28** |

---

### Yearly Cost
| Item | Cost (USD / Year) |
|----|------------------|
| Total Monthly × 12 | **$2,655.36** |

---

## Key Benefits
- High Availability with Load Balancer
- Scalable Laravel Architecture
- Dedicated Database Server
- Automated Backups
- Easy Deployment with Laravel Forge
- Optimized for High Traffic Applications

---

## Notes
- Prices are approximate and based on current EUR → USD conversion.
- Infrastructure can be scaled up or down based on project needs.
- Additional management and monitoring services can be added if required.

---

## Contact
**Company Name:**  
**Email:**  
**Phone / WhatsApp:**  
**Website:**  
