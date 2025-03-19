<img src="https://avatars1.githubusercontent.com/u/54474115?s=460&v=4" width="100" alt="" data-canonical-src="https://avatars1.githubusercontent.com/u/54474115?s=460&v=4">  &nbsp;&nbsp;
<img src="https://gamemonetize.com/images/construct3logo.png" width="100" alt="" data-canonical-src="https://gamemonetize.com/images/construct3logo.png">

# GameMonetize.com-SDK Construct 3
This repository contains the GameMonetize.com SDK for HTML5 Construct 3 games. This allows you to display advertisements in the games published within the GameMonetize.com network. https://GameMonetize.com

**UPDATE V2:** Downlaod update for Construct 3 (v2 support)

# STEP 1:
<a href="https://drive.google.com/file/d/1qwhm5drPwjzdWMc01qH-NQzTJmINGudG/">Download the plugin</a> or visit <a href="https://www.construct.net/en/make-games/addons/448/gamemonetize-com-sdk">Construct 3 Addons here</a>
- In your Construct3 project, go to Menu > View > Addon manager</br>
- Select and upload the .c3addon file you've just downloaded</br>
- Restart the editor (refresh your browser if you are using the online version https://editor.construct.net)</br>
- Double click your stage and select GameMonetize SDK</br>

<p><img src="https://gamemonetize.com/images/construct3/step1.png"  width="500" alt=""></p>

# STEP 2:
Select the new plugin within Construct 3 by right-clicking on Object Types and insert your Game ID in the properties tab.
You can find these values within your GameMonetize control panel after creating a new game.

# STEP 3:
Right-click Object types in the 'Projects' tab, select Insert New Object and select 'GameMonetize SDK' in the 'Monetization' category and insert your Game ID in from your account on game
<p><img src="https://gamemonetize.com/images/construct3/step2.png"  width="650" alt=""></p>

# STEP 4:
Add new action or event in your "Event sheet" - click to "Add action" or "Add event"
<p><img src="https://gamemonetize.com/images/construct3/step3.png"  width="650" alt=""></p>

# STEP 5:
You can now call the 'Show an Advertisement' action - whenever and as often as you want. We will make sure to reject any premature calls.
<p><img src="https://gamemonetize.com/images/construct3/step5.png"  width="650" alt=""></p>

# TIP: Pause / Resume event
Add events for pause and resume game. You have to stop your game and mute all sound & music when you see an advertisement.
<p><img src="https://gamemonetize.com/images/construct3/step7.png"  width="650" alt=""></p>

# Known issue
<p>Getting the error "ReferenceError: window is not defined" - since our JS file in SDK is hosted, please pay attention</p>
<p><b>Solution:</b> Click to "Timeline Basics" - left menu "Properties" - section "Advanced" - User worker - select "No"</p>
<p><img src="https://gamemonetize.com/images/construct3/step1011.png"  width="650" alt=""></p>

# FAQ
<h2>How to upload a game files?</h2>
<p><b>Answer</b>: When your game is ready to upload, you need to compress all game files to .ZIP file - Root folder of .ZIP file must include index.html and game files</p>
<h2><b>Implementation self-hosted games.</b></h2>
<p>In the case where a developer wants to self-host their game, please contact us on at: info@gamemonetize.com</p>

# Support:
If you have any technical questions or comments, please email us at:
info@gamemonetize.com

Or simply check documentation on:
https://gamemonetize.com/sdk
