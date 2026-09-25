# Rental Progress

This repository hosts the public GitHub landing page for the rental application tracker.

The real dashboard runs at:

https://metcalf-rental-progress.metcalftimothy0414.chatgpt.site

## Why the live tracker is separate

The live tracker uses a private Zillow email feed connection. That feed needs secret settings, so the actual private dashboard should not be copied directly into this public GitHub repository.

GitHub Pages is used as the easy entry point. The private tracker keeps handling the automatic updates.

## Current flow

1. Zillow sends application emails to the iCloud address.
2. iCloud forwards those Zillow emails into the connected Gmail pipeline.
3. The tracker reads the feed when the dashboard is opened or refreshed.
4. Tim and Viktoria can open the live tracker from this GitHub page.
