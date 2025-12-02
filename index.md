# Frontlify – Restaurant QR Feedback System

Welcome to Frontlify documentation! Frontlify helps restaurants and hospitality businesses collect instant customer feedback via QR codes.

## Overview
- QR-based feedback collection
- Mobile-friendly forms
- Real-time dashboard analytics
- Multi-location support
- Custom branding
- Paperless and fast

Explore the following sections to get started and maximize Frontlify for your business.
# Getting Started with Frontlify

## Step 1: Sign Up
Create an account on Frontlify.

## Step 2: Create Feedback Page
Build a mobile-friendly feedback page with ratings and comments.

## Step 3: Generate QR Code
Generate a unique QR code for your page.

## Step 4: Place QR Codes
Place them on tables, menus, receipts, or takeaway packaging.

## Step 5: Monitor Feedback
View all feedback in real-time from your dashboard.
# Features

## QR-Based Feedback
Guests scan a QR code and submit their ratings/comments.

## Real-Time Dashboard
View feedback instantly, track trends, and analyze customer satisfaction.

## Custom Branding
Add your logo, colors, and messaging to feedback forms.

## Multi-Location Support
Manage multiple branches and locations from a single dashboard.

## Easy Setup
No technical skills required; get started in minutes.
# Frequently Asked Questions

**Do customers need an app?**  
No, they can submit feedback directly via the QR code.

**Is Frontlify customizable?**  
Yes, you can add your branding and custom questions.

**Can I manage multiple locations?**  
Yes, the dashboard supports multi-branch management.

**Does it work for delivery and takeaway?**  
Yes, QR codes can be printed on receipts and packaging.
# Best Practices

- Place QR codes on every table and menu.
- Encourage guests to scan before leaving.
- Check feedback daily to catch issues early.
- Reward staff for positive feedback.
- Keep forms short and simple for higher response rates.
version: 2

build:
  os: ubuntu-22.04
  tools:
    python: "3.10"

mkdocs:
  configuration: mkdocs.yml
site_name: Frontlify Documentation

nav:
  - Home: docs/index.md
  - Getting Started: docs/getting-started.md
  - Features: docs/features.md
  - FAQ: docs/faq.md
  - Best Practices: docs/best-practices.md

