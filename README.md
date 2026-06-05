# WhatsApp Client Reporter - Landing Page Website

This repository hosts the public landing page for **WhatsApp Client Reporter** at:
https://nehalajmal.github.io/whatsapp-reporter-site/

## Direct UPI Payments

The landing page accepts payments directly using UPI to avoid platform fees:
- QR Code for Desktop users.
- Direct UPI App deep links for Mobile users.
- Redirects buyers to WhatsApp to send receipt screenshots for manual delivery.

## Local Sales Dashboard

To run the private local sales dashboard and track your sales:
1. Open your terminal in the script directory (`whatsapp_reporter`).
2. Run the dashboard:
   ```bash
   python3 dashboard.py
   ```
3. Open [http://localhost:8000](http://localhost:8000) in your browser.
4. Add transactions to your local `sales.json` database.
