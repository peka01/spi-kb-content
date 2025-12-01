---
title: Offline Mode for Mobile App
slug: mobile-offline-mode-for-mobile-app-1764583263538
format: md
status: draft
folderId: null
publishedAt: null
id: article-1764583279030-btd44jxs2
createdAt: '2025-12-01T10:01:19.030Z'
updatedAt: '2025-12-01T10:01:19.030Z'
metadata:
  productId: visma-spcs
  productArea: mobile
  featureCategory: offline-mode
  tags:
    - new_feature
    - mobile
  locale: sv-se
---
# Offline Mode for Mobile App

## Overview
Visma SPCS Mobile App introduces a new offline functionality, enabling you to continue working even without an internet connection. This feature allows you to create and edit invoices, view reports, and manage customer information seamlessly. All changes made while offline are automatically stored locally on your device and synchronized with the cloud once your internet connection is restored.

## Prerequisites
-   Visma SPCS Mobile App installed and updated to the latest version.
-   Sufficient storage space on your mobile device (up to 100MB per user is reserved for offline data).
-   Standard user permissions for accessing and modifying data within the app.

## Steps

### 1. Understanding Automatic Offline Functionality
The Visma SPCS Mobile App automatically detects your network status. If your device loses its internet connection, the app will seamlessly switch to offline mode, allowing you to continue performing most tasks. Your work is stored securely on your device until a connection is re-established.

### 2. Checking Your Connection Status
To quickly see if you are online or offline:
1.  Look at the new **StatusBar** usually located at the top of your app screen.
2.  This indicator will clearly show whether your current status is `{key_status_online}` or `{key_status_offline}`.

*(Screenshot placeholder: Image showing the StatusBar with online/offline status)*

### 3. Monitoring Data Synchronization
The new **SyncIndicator** provides real-time updates on your data synchronization status:
1.  Locate the **SyncIndicator** within the app (its exact position may vary slightly based on screen).
2.  It will display the number of `{key_pending_sync_items}` that need to be uploaded and the `{key_last_sync_time}` when data was last successfully synchronized.

*(Screenshot placeholder: Image showing the SyncIndicator with pending items and last sync time)*

### 4. Working Offline (Example: Creating an Invoice)
You can perform critical tasks like creating invoices even when offline:
1.  Navigate to the `{key_invoices_menu}` in the app.
2.  Tap on `{key_create_new_invoice}`.
3.  Fill in all the necessary details for your invoice.
4.  Tap `{key_save_button}`. The invoice is now saved locally on your device.
5.  In the `InvoiceList`, you will notice a status next to the newly created invoice indicating it is `{key_local_only}` or `{key_not_synced}`. This signifies that it is awaiting synchronization.

*(Screenshot placeholder: Image of the InvoiceList highlighting an invoice with a local/not synced status)*

### 5. Automatic Synchronization Upon Reconnection
Once your mobile device regains an internet connection:
1.  The Visma SPCS Mobile App will automatically begin synchronizing all locally stored changes with the cloud.
2.  The **SyncIndicator** will update as items are processed.
3.  After a successful sync, the status of your offline-created invoices (and other data) in the `InvoiceList` will change to `{key_synced}`.

## Related Articles
-   [Getting Started with Visma SPCS Mobile App]
-   [Managing Invoices in the Mobile App]
-   [Troubleshooting Connection Issues]
