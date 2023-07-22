
# Magz Firefox Customizations

Personal tweaks and edits Magz use for Firefox browser.

For now, includes:

- Custom "new tab" page and "homepage" (using Tabliss add-on and the Custom CSS option)

- Collapsible and "modern" vertical tabs that adapts to most Firefox themes (using Sidebery 5 add-on and Custom CSS)



## Screenshots and Demonstration

#### Screenshots:
![Example of Custom Homepage Tab](examples/Screenshot_1.jpg)

![Example of Custom Homepage Tab with vertical tab sidebar](examples/Screenshot_2.jpg)

![Example of Vertical Tab Sidebar in full menu mode](examples/Screenshot_3.jpg)

#### Videos:

Demonstration of Tabliss "custome homepage" and Sidebery 5 customization



https://github.com/cristaldotgema/Magz-Firefox-Tweaks/assets/22608199/6164746f-cffe-4333-bf1e-59d8d873cfd7



Vertical Sidebar Adapting to Different Firefox Themes



https://github.com/cristaldotgema/Magz-Firefox-Tweaks/assets/22608199/6e3833d1-2b10-48bd-a6c2-919e7b498361





#### Template:

Will see this when first import Tabliss data though:

![Tabliss base template](examples/tabliss_template.jpg)






## Installation

- Download this Github Repository as a .zip file

(Click the "Code" button, then "Download .Zip")

!["Code" button with drop-down menu showing "Download .zip"](https://github.com/cristaldotgema/Magz-Firefox-Tweaks/assets/22608199/562e6f2e-03b4-45c2-b260-8840b4dfb24e)

- Unzip the file somewhere you'll remember.

### The Custom Homepage Tab:

- Install [Tabliss](https://tabliss.io/) add-on. (or test out [the web version](https://web.tabliss.io/) first).
- Click the cog wheel (settings) on the new Tabliss page, scroll down and click "import" settings.

![Tabliss Import Settings Screenshot](examples/tabliss_settings.jpg)

- Import the "tabliss.json" file. It will be in the .zip file downloaded from the github repository, in the "Tabliss" section.

- This imports the base template with the few custom CSS tweaks and layout.
  
- On the Tabliss Change the text, the city used for the weather, the links shortcuts, upload images you want for the background, and anything else to suit your needs. 

### Vertical Tabs SideBar

- Install [Sidebery 5 beta](https://github.com/mbnuqw/sidebery) from the Github page.
  
- Approve the add-on installation and give it permission to be enabled during private browsing when it asks (otherwise, won't have visible tabs later on).

- Type ``about:config`` in browser url bar. Search ``toolkit.legacyUserProfileCustomizations.stylesheets`` and change to "true", if it wasn't before. This allows for browser profile customization.

  ![About config's setting changed to "true"](https://github.com/cristaldotgema/Magz-Firefox-Tweaks/assets/22608199/cf5289a0-941a-4df6-afe5-c54c4f7ba7f4)


- Type ``about:profiles`` and click the "root directory"s "open folder" button.

  ![About profile's root directory folder button](https://github.com/cristaldotgema/Magz-Firefox-Tweaks/assets/22608199/0065fd84-cec5-44a3-a96c-9f3eb0d3a3b4)


- Copy-Paste or drag the "chrome" folder in the Firefox tweaks unzipped file, into the root directory folder.

  ![Dragging the "chrome" folder into the Firefox root directory](https://github.com/cristaldotgema/Magz-Firefox-Tweaks/assets/22608199/2a6a85cb-f961-47b2-9cce-b78a0692bf60)


- Copy-Paste the "sidebery" folder into the "chrome" folder, or have the "sidebery" folder somewhere that won't get accidentally deleted.

- Right-click the Sidebery Sidebar or the Sidebery add-on icon on the Firefox browser. Click "open settings" or "configure panel".
!["open setting" button for Sidebery button](https://github.com/cristaldotgema/Magz-Firefox-Tweaks/assets/22608199/e0de0c19-0804-43ad-986d-a200274c65cb)


- In the Sidebery Settings menu, click "help" section, then "import add-on data" and select the "sidebery-data.json" file in the "sidebery" folder from unzipped github folder.

  !["Import add-on data" button on Sidebery's help section of settings](https://github.com/cristaldotgema/Magz-Firefox-Tweaks/assets/22608199/8e4323ca-81a0-4103-9617-8296181dbaa9)

!["Sidebery-data.json" file highlighted](https://github.com/cristaldotgema/Magz-Firefox-Tweaks/assets/22608199/3d3d5cda-cc3d-425a-b39e-75f11bbcdf77)

- Close Firefox, and open it again for both the Sidebery style settings and the Browser settings to take effect.

Can change general settings of the sidebar in sidebery's settings - like if it's on the left or right

Optionally: Can change the position of the sidebery bar icon on the top menu bar, to be closer to the sidebar by right clicking and choosing "customize toolbar".

!["Customize toolber" option that appears when right-clicking the top menu bar](https://github.com/cristaldotgema/Magz-Firefox-Tweaks/assets/22608199/ae06ed08-6cac-4981-9052-952af5ad066b)

  
## Acknowledgements / Credits

### Code:
- [Firefox Vertical Tabs](https://github.com/ranmaru22/firefox-vertical-tabs) by ranmaru22. (Used the "userChrome.css" from this, for the upper menu bar tweak and taking off horizontal tab - originally intended to be used with a different sidebar add-on)

- ["Yet another Sidebery setup"](https://www.reddit.com/r/FirefoxCSS/comments/rmi8dg/yet_another_sidebery_setup/) by a deleted Reddit user. (Used the "userChrome.css" from this - that makes the sidebar collapse when not hovered and so on. Used the sidebery stylesheet as a base for appearance, but heavily edited and changed code - it wasn't fully working 2 years later after all)

- [Tabliss's developer](https://github.com/joelshepherd/) - The homepage setup uses the Tabliss add-on

- [Sidebery's developer](https://github.com/mbnuqw/) - The sidebar uses the Sidebery add-on

### Featured Graphics and themes:

These were used in the demonstration as example images. They are not in the github repository, nor being redistributed as part of customization setup.

#### Example Background Images by:
- _ Roitz _ 
- killian ng 
- nymria 
- Senbon Umishima 
- siun_5513 
- sumi
- swdrk_ 
- lirseven 
- zephyo

#### Example themes:
- Dark neon. 
- Carribean Current.
- Dark.
- Dark Pink (pink).
- Firefox Alpenglow.
- Innovator (Bold).
- Light.
- Lush (Bold).
- Matte Black (pink).
- Rainbow Pastel.
- Stained Glass.



#### Time:
(For reference: Published July 21, 2023 - using latest Firefox at time, version 115.0.2)
