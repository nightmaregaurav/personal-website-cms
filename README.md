# Micro CMS for statically hosted personal website [Personal Website CMS]
This minimal CMS runs using client side technology so that it can also be hosted on a server that can only host static websites. It uses JSON api to make things Dynamic. It provides Setup GUI to allow editing the website contents and configuration.
<br>
`It's not jekyll.` `Personal-Website-CMS` is built using React and depends on one or more configuration files. This app uses the [React Router](https://reactrouter.com/) library to make routing easier.

![](1.png)

| ![](2.png) | ![](3.png) |
|:----------:|:----------:|

# Features
* ### Classic Features
    * About Page
    * Education Page
    * Experience Page
    * Projects Page
    * Individual project's page
    * Gallery Page
    * Services Page
    * Skills Page
    * Contact Page
    * Setup Page
* ### Additional Features
  * Completely dynamic setup.
  * Dynamic content is generated on the fly.
  * Dynamic content is generated using JSON api.
  * Supports GitHub Pages (and give extra features like saving configuration on button click).
  * Fast and easy to set up.
  * Cheap to host static project on a server.
  * Complete customization.

## Installation
* ### On GitHub pages
  1. Fork the repository, preferably with name `{your-username}.github.io`
  2. Go to settings and enable GitHub pages
  3. Add CNAME and change the domain name to your domain name or setup domain name from your repo setting.
  4. Perform Step 3 & 4 of [Upgrade Section](#upgrade).
  5. Follow Steps in [Maintenance Section](#maintenance) for website setup and customization.

* ### On your own server
  1. Open terminal inside `public_html` or `wwwroot` or equivalent folder. (referred as `www-folder`).
  2. Run `git clone https://github.com/nightmaregaurav/personal-website-cms.git .`
     * Make sure the `www-folder` is empty before you perform this step.
  2. Perform Step 3 & 4 of [Upgrade Section](#upgrade).
  3. Follow Steps in [Maintenance Section](#maintenance) for website setup and customization.

## Opening Setup UI
* Navigate to `<root>/setup` URL
* That may fail to work in some cases.
* Use the key you chose in previous setup with Ctrl+Shift+Alt (Default key is `s` if you haven't set any).

## Maintenance
1. Open setup page.
2. Make Changes.
3. Click `Save config.json`
   * For GitHub Page, it will automatically commit and push the changes to the repository.
   * For other hosting, you have to manually commit and push the changes(or upload) to the server.
4. Wait for the changes to take effect. (It may take 1 to 5 minutes, Check your website to verify).
5. Reopen and reload setup page.
6. Click `Save sitemap.xml`
   * For GitHub Page, it will automatically commit and push the changes to the repository.
   * For other hosting, you have to manually commit and push the changes(or upload) to the server.
7. Sit back and relax.

## Upgrade
1. Pull from upstream or Sync fork.
2. Open setup page.
3. Click `Fix 404.html`. 
   * For GitHub Page, it will automatically commit and push the changes to the repository.
   * For other hosting, you have to manually commit and push the changes(or upload) to the server.
4. Click `Fix index.html`.
   * For GitHub Page, it will automatically commit and push the changes to the repository.
   * For other hosting, you have to manually commit and push the changes(or upload) to the server.
5. Done

### IMPORTANT
* #### It is recommended that you DO NOT add/modify files in the repository manually unless you really know what you are doing.
* #### If you need to serve static files in any special case, you can do so in and only in 'data' folder in the root of the repo</b>

### Sometimes, those who view this repository are looking for the [Source Repository](https://github.com/nightmaregaurav/personal-website-cms-source)

## This repository is only for
* Forking/Cloning and hosting the website.
* Discussion related to non-technical topics related to this CMS.

---
## Note: This Project is Licensed under GNU GPLv3.

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
For Issues, Contributions, and Source Code: Visit the [Source Repository](https://github.com/nightmaregaurav/personal-website-cms-source)
---
