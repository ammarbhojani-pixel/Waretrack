# WareTrack — Clothing Bale & Warehouse Manager

A lightweight, responsive front-end prototype for tracking clothing bales across suppliers, warehouse stock, sales, and dispatch.

## Features
- Dashboard counts for total bales, warehouse stock, supplier-held stock, and sold/dispatched bales
- Bale registration with category, weight, quality rating, status, and location
- Searchable bale inventory
- Stock movement logging with status updates
- Supplier directory
- Sales and dispatch register that marks a bale as sold
- Browser-local persistence using `localStorage`
- Responsive layout for desktop and mobile browsers

## Run locally
Open `index.html` in a modern browser. No build step or server is required.

## Demo-data and storage warning
This is a prototype, not a production inventory system. It starts with illustrative sample records. Data changes are saved only in the current browser profile and device. There is no login, shared database, cloud backup, server synchronization, or audit-grade access control. Do not store confidential customer, supplier, or financial data in this demo. Replace the local storage layer with an authenticated backend/database before real business use.

## Deploy with GitHub Pages
1. Create a GitHub repository named `WareTrack` under your account.
2. Upload `index.html` and `README.md` to the repository's root (main branch).
3. In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. Wait for GitHub Pages to finish the deployment; the public site URL will be shown in the Pages settings.

## Owner
Prepared for `ammarbhojani-pixel`.
