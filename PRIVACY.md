# Privacy Policy

**Effective Date:** September 22, 2026

## Overview
This Privacy Policy outlines how the **Anvil: D&D Beyond Magic Item Importer** ("Anvil", "we", "our", or "us") Chrome Extension collects, uses, and protects your information.

## Data Collection
Anvil is designed to operate locally on your device. We **do not** collect, transmit, store, or sell your personal data. 
- All data parsed from text inputs and written to D&D Beyond remains strictly within your active browser session.
- The extension stores minor configuration data locally on your device (using `chrome.storage.local`), such as your preferred default spell casting class and daily usage counters.
- If you activate an Anvil Pro license key, the key is verified directly against Gumroad's official API and stored securely in your local browser storage. We do not track or store your key remotely.

## Permissions Usage
The extension requires specific permissions solely to perform its core function (automating the D&D Beyond website interface):
- **Host Permissions & activeTab:** Used to interact with `dndbeyond.com` pages to programmatically fill out magic item creation forms.
- **Storage:** Used to save your local extension preferences.
- **Tabs:** Used to read the URL of your active tab to ensure the extension only runs when appropriate, and to open initialization pages.
- **Downloads:** Used entirely for a local "Export Diagnostics" feature that allows you to download debug logs if an error occurs. 

## Third-Party Services
We use **Gumroad** as a third-party payment and license verification provider. When you verify an Anvil Pro license key, the extension communicates directly with Gumroad's API to validate the key. Your purchase history and payment information are handled securely by Gumroad; Anvil does not have access to this information.

## Changes to this Policy
We may update this Privacy Policy occasionally to reflect changes in our practices. We encourage you to review it periodically.

## Contact Us
If you have any questions or concerns regarding this Privacy Policy or your data, please contact the developer via the support links provided in the Chrome Web Store or our GitHub repository.
