---
title: "Tools On Board"
description: "This is the list of the tools on board"
draft: false
tags: ["Featured", "Tools","Tool"]
images: ["tools.webp"]
keywords: ["Tools", "tool", "power tools"]
---

# Tools onboard

Improve code health of your web page following these best practices.

## Power tools
1. Bosch cordless drill
2. Bosch cordless screw driver 
3. Bosch batteries - 2 sets 
4. Bosch battery chargers - 2 sets 

## Racheting tools 
1. 3/4 inch torque limiter racheting driver 
2. 1/2 inch racheting driver 
## Screwing/Fastening Tools
1. Wiha 32093 Slotted and Phillips Insulated Screwdriver Set, 1000 Volt, 10 Piece
- Set Includes: Slotted 2.0, 2.5, 3.0, 3.5, 4.5, 6.5mm | Phillips #0, #1, #2, #3
2. 
## Cutting Tools 
## Striking Tools 

## Use HTTPS

All websites should be protected with HTTPS, even ones that don't handle sensitive data. HTTPS prevents intruders from tampering with or passively listening in on the communications between your site and your users.

## External Links

When you link to a page on another site using the target="_blank" attribute, you can expose your site to performance and security issues:

- The other page may run on the same process as your page. If the other page is running a lot of JavaScript, your page's performance may suffer.

- The other page can access your window object with the window.opener property. This may allow the other page to redirect your page to a malicious URL.

Adding `rel="noopener"` or `rel="noreferrer"` to your `target="_blank"` links avoids these issues.

---

All external links will have `target="_blank"` and `rel=“noopener nofollow”` attribute.

- [Salvus.Site](https://salvus.site)

- [Render-link.html help need](https://discourse.gohugo.io/t/render-link-html-help-need/30006/3)

Internal link:

- [Blog](/blog/)

## Checks your JavaScript libraries for security vulnerabilities

Intruders have automated web crawlers that can scan your site for known security vulnerabilities. When the web crawler detects a vulnerability, it alerts the intruder. From there, the intruder just needs to figure out how to exploit the vulnerability on your site.

To detect vulnerable libraries check [snyk's Vulnerability DB](https://snyk.io/vuln?packageManager=all).

## Configure Content Security Policy (CSP)

A Content Security Policy (CSP) helps to ensure any content loaded in the page is trusted by the site owner. CSPs mitigate cross-site scripting (XSS) attacks because they can block unsafe scripts injected by attackers. However, the CSP can easily be bypassed if it is not strict enough.

