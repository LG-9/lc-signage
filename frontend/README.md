lc-livesignage_frontend_README

Created by LG [lucas@madisonlibrary.org]

Madison County Public Library, KY, USA

https://madisonlibrary.org/


README.md 		:: This file.

TEMPLATE.html 	:: Template file from which all signage pages can be generated.

lc-signage.css 	:: CSS file for lc-signage.

lc-signage.js 	:: JavaScript file for lc-signage.


lc-LiveSignage frontend uses a basic HTML page driven by JavaScript and CSS.

For each sign, create a HTML file from TEMPLATE.html.

Modify events.css and events.js to fit your needs.


Required:

 [ROOM_NAME] = name of the room

 [JSON_FILE] = path to the json file to be parsed


Optional:	

 [LOGO_IMG] = path to company logo image

 [QRCODE_LINK] = URL to be embeded in the 'more info' QRcode

 [PUBLIC_TRUE] = path to 'public' event denotion image

 [PUBLIC_FALSE] = path to 'private' event denotion image