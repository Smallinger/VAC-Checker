# VAC-Checker
A  Tamper-/Greasemonkey script to check for Steam VAC Bans

# How to use

1. Install [Tampermonkey for Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en) or [Greasemonkey for FireFox](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/).
2. Open view the Raw code for [VAC-Checker.user.js](https://github.com/Junxx/VAC-Checker/raw/master/VAC-Checker.user.js)
3. Install the script in Tempermonkey or Greasemonkey
4. Navigate to your [friends recently played with](http://steamcommunity.com/my/friends/coplay) page.
5. The script will use automatic the Steam API to get a list of VAC bans for those users on that page :wink:.

Pro tip: This script also works on your friend's friends list! Just go to their profile page, click "Friends" on the right panel, And see their friend's vac bans!

### How to install: visual instructions

![Instructions](https://raw.githubusercontent.com/Junxx/VAC-Checker/master/instructions.gif)

# HTTPS

- Valve blocked any traffic from any non-Valve official URLs.
- For some strange reason Valve blocks their API when you use HTTPS.
- You can Google the error that gets displayed in console for more info.
- Solution is open the HTTP site of [the friends list](http://steamcommunity.com/my/friends/coplay)

# Changelog

1.0b2 - added Steam Community Groups!  
1.0b1 - first script Released!

# Credits

Credits go out to [MrHayato](https://github.com/MrHayato). His idea inspired me to write a version that can be easily used as a tamper-/greasemonkey script.
