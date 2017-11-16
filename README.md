# Omnis-DirectHTTP
Library shows how you can interact with Omnis directly via HTTP forms.

Requires Omnis Studio 8.1.2 or above.

## Contents
### DIRECTHTTP
This folder contains the source JSON files for the Omnis library in Github. 

To restore these files in Omnis Studio, click on the Libraries option in the Studio Browser, and click on the New Lib from JSON option. In the New Library (import) dialog, navigate to this source folder (containing library.json), and then specify a different folder or location for the new Library. Click on Import and open the library in the Studio Browser. 

After you import the library you need to set the $serverport preference to 5912 (the port number needs to match the setting in the HTML page); to set this in Omnis, click on Omnis in the Studio Browser, click on Prefs and set $serverport in the Property Manager.
