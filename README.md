# SwitftPos_group3_cloudcomputing
# SwiftPOS — SaaS Point-of-Sale Application

A web-based multi-tenant Point-of-Sale system built as a SaaS solution.

##  Live Demo
https://swiftpos-group3-mid.s3.ap-southeast-1.amazonaws.com/index.html

##  Features
- Multi-tenant support (data isolated per tenant)
- Product management per tenant
- Sales transaction processing
- Digital receipt generation
- Email receipt delivery via EmailJS

##  Architecture
- **Frontend**: HTML, CSS, Vanilla JavaScript
- **Hosting**: AWS S3 (static) + AWS CloudFront (CDN)
- **Email**: EmailJS (browser-side email delivery)
- **Storage**: localStorage (per-tenant data isolation)

## 👥 Multi-Tenant Demo Accounts
| Tenant | Email | Password |
|--------|-------|----------|
| Sunrise Café | cafe@demo.com | demo123 |
| TechMart | tech@demo.com | demo123 |
| StyleHub | fashion@demo.com | demo123 |
| FreshMart | grocery@demo.com | demo123 |

##  How to Run Locally
Just open `index.html` in any browser — no build step required.

##  Deployment
Hosted on AWS S3 with CloudFront distribution.
