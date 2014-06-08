Zim-export-template-responsive
==============================

ZIM-Wiki export template

An template to export ZIM-wiki notebooks as a website, as explained here: http://zim-wiki.org/manual/Help/Export.html.

The website uses jquery and jquerymobile to create responsive webpages with an index in a side panel. The webpages should therefore look good on the desktop or your mobile device.

http://pvanb.wordpress.com/2014/06/06/a-zim-wiki-export-template-for-a-adaptive-website/

## Installing the template


You can pull the files to a temporary folder, and copy the ecodiv.html and ecodiv folder to the ~/.local/share/zim/templates/html

```bash
cd
mkdir tempzim
cd tempzim
git clone https://github.com/ecodiv/Zim-export-template-responsive.git
cd Zim-export-template-responsive
mv ecodiv.html ~/.local/share/zim/templates/html
mv ecodiv ~/.local/share/zim/templates/html
```

After this you can delete the tempzim folder if you like or leave it, to get updates from the github repository.

Note that you do not need to move the ecodiv.html and ecodiv folder to the ~/.local/share/zim/templates/html folder. It is convenient as it makes the template available through the drop down menu (File --> Export) and it is available through Edit --> Template. However, when exporting you can always select a template from any location on your computer. So, if you copy the ecodiv.html and ecodiv folder to e.g., your Documents folder, you can then select the ecodiv.html from the File --> Export menu.

But whatever solution you go for, just make sure to copy the folder ecodiv to the same folder as the ecodiv.html file, otherwise the result will not be as intended.

