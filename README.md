# A Joomla4 mod_dashboard override
This is an override for the mod_dashboard module by Yannick Berges (@Micker) - https://github.com/micker/mod_dashboard for use with the Atum template and published to the "**icon**" position. 

The override is intentionally built to _ONLY_ include the "custom message" area & the "tabbed" sections of the existing module and ignore other settings/options as we rarely used any of the other options and just wanted a simple _custom most used Client Administration dashboard panel_.

## How to use this override
1) copy the override files to the Atum templates "/html/" folder
2) set module "Postion" to "icon" in mod_dashboard
3) select "Advanced" tab > "Layout option" and choose "**j4-iconview**" in mod_dashboard
4) optionlly, re-order the module to the preferred position in the module list


### Override Locations
- /administrator/templates/atum/html/mod_dashboard/
- /administrator/templates/atum/html/mod_dashboard/j4-iconview.php
- /administrator/templates/atum/html/mod_dashboard/css/j4-iconview.css

![Screen Shot 2021-10-08 at 4 25 56 pm](https://user-images.githubusercontent.com/871931/136508587-f8d27860-86bb-4d4e-80dd-834971459806.jpg)
