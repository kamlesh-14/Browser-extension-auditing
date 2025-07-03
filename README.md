# Browser-extension-auditing

## Browser Extension Audit – Suspicious Extension Removal

## Objective
Identify and remove potentially harmful or unnecessary browser extensions to improve security and performance.

## Tools Used
Browser: Google Chrome

Accessed via: chrome://extensions/

 Extension Reviewed
Extension Name: Super Video Speed Controller
Version: 1.3.2.1
Size: 1.1 MB
Source: Chrome Web Store
Permissions Requested:
Read and change all your data on websites you visit
Run in incognito mode
Access to file URLs
Site access: All sites

## Security Analysis
 High-Risk Permissions: Full site access is excessive for its functionality
Can Record Sensitive Data: Permissions may allow keylogging, session hijacking, or content spying
Unverified Developer: No developer information or verification badge
Privacy Concern: May collect user data from all websites visited

## Action Taken
Marked as suspicious due to over-permission
Removed from Chrome
Browser restarted to complete the cleanup
Verified performance improvement and ensured no leftover traces

## What I Learned
How to analyze browser extension behavior and permissions
Identified signs of overreach in extensions
Practiced safe browser hygiene by regularly auditing extensions
Understood how attackers can use browser extensions as spyware

## What’s the difference between extensions and plugins?
Feature	Extensions	Plugins
 Purpose	Add or enhance browser functionality (e.g., ad-blockers)	Support specific content types (e.g., Flash, Java Applets)
 Runs In	Browser environment only	External to browser, but integrated with it
 Installed From	Browser's official extension store	Installed separately from third-party sources
 Current Use	Actively used and supported in modern browsers	Mostly deprecated and no longer widely supported

# Conclusion: Extensions are safe browser add-ons when vetted, whereas plugins are older technologies now mostly phased out due to security concerns.

## How to report malicious browser extensions?
If you find a suspicious or malicious extension:

 For Google Chrome:
Go to the Chrome Web Store page.
Search for the extension name.
Scroll down and click "Report abuse".
Fill out the reason (e.g., collects sensitive data, behaves maliciously).
Submit the form.

 For Mozilla Firefox:
Visit Firefox Add-ons.
Open the extension page.
Click "Report this add-on for abuse" at the bottom.
Choose the issue and provide a short description.
🛡️ Reporting helps protect other users and keep the browser ecosystem safe.
