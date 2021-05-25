# userChrome.css Tweaks for Firefox

## Getting Started
### Enable userChrome.css in Firefox
* Navigate to about:config in Firefox
* Search for `toolkit.legacyUserProfileCustomizations.stylesheets`
* Set `toolkit.legacyUserProfileCustomizations.stylesheets` to True

### Create userChrome.css
*Thanks to https://www.reddit.com/r/FirefoxCSS/comments/73dvty/tutorial_how_to_create_and_livedebug_userchromecss/ for these instructions.*
* Navigate to about:support in Firefox
* Click on "Profile Folder" -> "Open Folder"
* Create a sub-folder named "chrome"
* Open the chrome folder
* In the chrome folder, create a file named "userChrome.css"

### Editing userChrome.css
* At the top of your stylesheet, add `@namespace url("http://www.mozilla.org/keymaster/gatekeeper/there.is.only.xul");`
* Add rules beneath `@namespace url("http://www.mozilla.org/keymaster/gatekeeper/there.is.only.xul");`
* Restart Firefox

### Enable Browser Toolbox to Help You Create Your Own Rules (Optional)
* Open developer tools
* Click the three dots to the right of the dev tools window
* Go to settings
* Under advanced settings, check `Enable browser chrome and add-on debugging toolboxes` and `Enable remote debugging`
* Open Web Developer > Browser Toolbox to inspect browser elements
