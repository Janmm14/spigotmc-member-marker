# SpigotMC member marker
Fast and easy spigotmc member marker

Saves data in javascript local storage (browser). Currently no data deletion feature implemented - use devtolls to remove from local storage

Member list textarea has deduplucation, new entries added to the bottom.

Intended for 1080p monitor fullscreen, maybe with 80% browser zoom or so.

## Setup
1. Use Firefox browser.

   **_If Firefox is your daily driver_**: Download **_another_** firefox version like nightly, esr, beta or a firefox work like waterfox or librewolf and make sure it uses a different profile from your daily driver.

2. Download plugin Stylus: https://addons.mozilla.org/de/firefox/addon/styl-us/
   - Install my spigotmc theme newdark: https://userstyles.world/style/4051/spigotmc-newdark to remove the big header (maybe disable OLED option of style)
   - Import [spigotmc-member-check.css](https://github.com/Janmm14/spigotmc-member-marker/blob/main/spigotmc-member-check.css)
3. Download plugin https://addons.mozilla.org/en-US/firefox/addon/allow-sso-iframes/
4. Go to `about:config`
   - Set `network.cookie.cookieBehavior` to `0`
   - Set `privacy.partition.network_state` to `false`
   - Set `privacy.firstparty.isolate.restrict_opener_access` to `false`

   (Idk if all 3 options needed, didnt check whether less works, but with these 3 setting it works for me)

5. Open spigotmc in separate tab to pass cloudflare challenge
6. Then open index.html

## Keybinds
| Keybind | Action |
| ------- | ------ |
| Arrow left | Go back 4 user-ids |
| Arrow right | Go forward 4 user-ids |
| 1, 2, 3, 4 | Reload iframe 1, 2, 3 or 4 |
| q, w, e, r | Toggle checkbox for iframe 1, 2, 3 or 4 |
| a, s, d, f | Toggle iframe 1, 2, 3 or 4 to/from user's posts |

## Credits
Created with help of ChatGPT
