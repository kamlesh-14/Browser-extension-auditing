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
