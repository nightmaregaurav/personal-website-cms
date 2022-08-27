# Statically hosted dynamic personal website

This project runs using client side technology so that it can be hosted on a server that can only host static websites. But it uses JSON api to make things Dynamic(Kind of).
<br>
If you are not reading this from the `Personal-Website-Client` Repository of `NightmareGaurav`, then follow this <a href="https://github.com/nightmaregaurav/personal-website-client">link</a>.

![](1.png)

| ![](2.png) | ![](3.png) |
|:----------:|:----------:|

## Installation
### On GitHub pages
1. Fork the repository
2. Go to settings and enable GitHub pages
3. Change path of main static files (css and js) in `index.html` to match your hosting path IE: <your-website-root>
4. Change line `let home = "";` in `404.html` to `let home = "<YOUR HOME URL in github page>"` if you are using path other than / as root, normally happens when you are not using custom domain 
5. Copy `config.dist.json` as `config.json`
6. Change the data in `config.json` to match your data 
7. Keys in `config.json` are self-explanatory. But if you should need guidance, make sure to read `config-info`
8. Add CNAME and change the domain name to your domain name or setup domain name from your repo setting 
9. Visit `https://<your-website-root>/gh-sitemap/<your-website-root>` to generate sitemap 
10. Copy all content of sitemap and save as `sitemap.xml`
### On your own server
1. Clone the repository 
2. Change path of main static files (css and js) in `index.html` to match your hosting path IE: <your-website-root>
3. Change line `let home = "";` in `404.html` to `let home = "<YOUR HOME URL>"` if you are using path other than / as root 
4. Copy `config.dist.json` as `config.json`
5. Change the data in `config.json` to match your data 
6. Keys in `config.json` are self-explanatory. But if you should need guidance, make sure to read `config-info`
7. Visit `https://<your-website-root>/get-sitemap/<your-website-root>` to generate sitemap 
8. Copy all content of sitemap and save as `sitemap.xml`
 
## Maintenance
1. Update `config.json`
2. Update `sitemap.xml` using previous steps if you added or removed projects or enabled/disabled gallery

## Upgrade
1. Pull from upstream
2. Update `config.json` if there are any changes in config.dist.json or config-info
3. Update `sitemap.xml` if needed
4. Perform step 3 and 4 of `installation > On GitHub pages` if you are using GitHub pages
5. Perform step 2 & 3 of `installation > On your own server` if you are hosting it on you own server.

## Features
* Completely dynamic setup.
* Dynamic content is generated on the fly.
* Dynamic content is generated using JSON api.
* Fast and easy to use.
* Cheap to host static project on a server. Many trusted free hosts are also available.
* Complete customization.

---

## Note
- Project is Licensed under GNU GPLv3.

### Which means Anyone are permitted for:
- Commercial use: **The licensed material and derivatives may be used for commercial purposes.**
- Distribution: **The licensed material may be distributed.**
- Modification: **The licensed material may be modified.**
- Patent use: **This license provides an express grant of patent rights from contributors.**
- Private use **The licensed material may be used and modified in private.**

### Under Condition that:
- Disclose source: **Source code must be made available when the licensed material is distributed.**
- License and copyright notice: **A copy of the license and copyright notice must be included with the licensed material.**
- Same license: **Modifications must be released under the same license when distributing the licensed material. In some cases a similar or related license may be used.**
- State changes: **Changes made to the licensed material must be documented. Along with link to original source**

---
Currently, not open For contribution. Issues and Suggestions are welcomed
---
