---
title: Offline Mode for Mobile App
slug: mobile-offline-mode-for-mobile-app-1764577383354
format: md
status: draft
folderId: null
publishedAt: null
id: article-1764577383363-orjdgu70m
createdAt: '2025-12-01T08:23:03.363Z'
updatedAt: '2025-12-01T08:23:03.363Z'
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
Implemented offline functionality allowing users to work without internet connection. Data syncs automatically when connection is restored.

## User Impact
Users can now create and edit invoices, view reports, and manage customers even without internet connection. All changes sync automatically when back online.

## UI Changes
- **StatusBar** (new): Added connection status indicator showing online/offline state
- **SyncIndicator** (new): Shows pending sync items and last sync time
- **InvoiceList** (update): Updated to show local/synced status for each invoice

## Additional Information
Uses IndexedDB for local storage. Conflict resolution prioritizes most recent timestamp. Maximum offline storage: 100MB per user.

---
*This article was auto-generated from manifest KNY7KNNyEP3KLOT7H9Ih*
