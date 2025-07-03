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
Extensions are lightweight add-ons installed directly from a browser’s official store (like Chrome Web Store) to enhance or modify browser functionality—such as ad-blockers, password managers, or productivity tools. They run within the browser environment and are sandboxed for security. Plugins, on the other hand, were external software components used in older browsers to render special types of web content like Flash or Java Applets. Plugins required separate installation and often had deeper system access, making them more vulnerable to security risks. Most modern browsers have now phased out plugin support in favor of safer and more controlled extensions.

## Conclusion: Extensions are safe browser add-ons when vetted, whereas plugins are older technologies now mostly phased out due to security concerns.

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
