# Usage

You should now see the Beta Protection extension in your Chrome extensions window. 

If you don't see the extension icon (look for the pink lock icon) in your browser toolbar, click the Extensions button (the puzzle piece) in your Chrome toolbar, find Beta Protection in the list and click the small pin icon beside it. This will pin Beta Protection to your toolbar so its always visible.

Click the icon in the toolbar to open the popup and check on your extension. At the top of the screen will be the connection status. If this does not show Connected, make sure your backend is running.

<Note type="info">

If you have your backend running somewhere other than your local PC, open the settings using the cog in the top right and change your backend host.

</Note>

<ImageZoom 
  src="../assets/chrome_popup.jpg" 
  :border="true" 
  width="300"
/>

From here, you can change the most common settings like the censoring mode and video censoring mode. If you want to customize Beta Protection though, click the Settings icon in the top right of the popup to open the full options page.

> You can also right-click on the icon in the toolbar and click `Options` to directly open the options page.

From the options page, you can directly customize basically any part of the extension. Generally, the options page will explain what each option does so make sure to read the tips as you change things.

### Placeholders

When you first install the extension, there will not be any placeholders, so images will be replaced by a simple loading icon while they are being censored. It's generally more fun to have placeholder images appear while censoring is running, so we recommend importing some placeholders to get started.

The easiest option is to import the placeholders from Beta Safety. From the Beta Protection options page, open the Placeholder Store section, click `Import from Beta Safety...` and choose the `placeholders` folder from your Beta Safety folder (usually in `browser-extension/images/placeholders`) and Beta Protection will import all the placeholders from that folder.

Alternatively you can use the `Import Folder...` or `Import Single File...` buttons to import placeholder images directly.

> Make sure you enable any newly added placeholder categories in the _Placeholders and Stickers_ section in the options after you import new placeholders.

### Context Menus

On any page, you can right-click to get a few extra options to control the extension. 

- *Enable censoring this tab* will force-enable censoring for the current tab, regardless of whether it otherwise would be. 
- *Recheck images on this page* will re-run censoring on a censored page, mostly useful if a page still has placeholders left that seem to have failed.