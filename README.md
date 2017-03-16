# whatsapp_skinchanger
Changes the skin of WhatsApp Desktop Application

# Pre Requirements
- node.js (https://nodejs.org/en/download/)
- npm (download of node.js should include it)
- asar(install it with: "npm install -g asar")
- a skin you want (maybe from here...: https://userstyles.org/styles/browse/whatsapp)

# Important for Skin
It should be "pure" CSS (so if you got it from userstyle.org you have to remove the '@-moz-document url-prefix("https://web.whatsapp.com/") {' and the closing '}')
Put the rest into the "patchedCSS.css" file.

# How to Patch
Make sure Whatsapp Desktop Application is closed. Put all files into the resources folder (e.x. on windows: "C:\Users\USERNAME\AppData\Local\WhatsApp\app-0.2.3699\resources" ..the app-X.X.XXXX folder changes every update ...took the lates one)

1.) Start Step1 wait until done. 
2.) Start Step2 wait until done (should be instantly). 
3.) Start Step3 wait until done. 

Finished, start WhatsApp Desktop now. If the skin messed up....check the patchedCSS.CSS file .. the error is there ¯\_(ツ)_/¯
