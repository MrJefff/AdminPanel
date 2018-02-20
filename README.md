A small GUI panel of clickable commands for admins

The Admin Panel plugin allows admins with the group title "admin" or permission the ability to have clickable admin buttons that are easy to get too.

How this plugin works. When a admin wakes up the panel is loaded. You'll notice the buttons next to your health. To access these buttons all you have to do it press enter to open up your chat so that your mouse can get released. then all you have to do is click.

## Dependencies

### Optional

- [Vanish](https://umod.org/plugins/vanish)
- [GodMode](http://oxidemod.org/plugins/godmode.673/)
- [N-Teleport](http://oxidemod.org/plugins/n-teleportation.1832/)
- [AdminRadar](https://umod.org/plugins/adminradar)
- [Update Checker](https://umod.org/plugins/updatechecker)

## Permissions

This plugin uses Oxide's permission system. To assign a permission, use oxide.grant user <name or steam id> <permission>. To remove a permission, use oxide.revoke user <name or steam id> <permission>.

- **adminpanel.allowed** -- (Gives a player the ability to see the adminpanel)

**Ex.** grant user austinv900 adminpanel.allowed

**Ex.** revoke user austinv900 adminpanel.allowed

**Ex.** grant group admin adminpanel.allowed

## Chat Commands

- **/adminpanel show** -- Show/Refresh the adminpanel
- **/adminpanel hide** -- Hide the admin panel
- **/adminpanel settp** -- Allows admin to set the tp location

## Toggle Feature

`bind h "+adminpanel toggle"` -- Console key bind

The toggle feature can come in handy for people the don't want to see the panel all the time. How it works is if it is enabled in the config you can hold the `H` key to open the panel and will then release your cursor to click on it. To close the menu just release the `H` key.
**This requires you to manually input the key bind.**

## Configuration

```json
{
  "AdminPanelPosMax": "0.986 0.36",
  "AdminPanelPosMin": "0.838 0.14",
  "AdminPanelToggleMode": true,
  "AdminZoneCoordinates": "-392 22.9 -312.3",
  "PanelButtonActiveColor": "0 2.55 0 0.3",
  "PanelButtonInactiveColor": "2.55 0 0 0.3",
  "ServerBannerImage": "banner.png"
}
```

## Localization

The default messages are in under the oxide/lang directory, or create a language file for another language using the 'en' as a default.
 
***AdminPanel.json***

```json
{
  "Title": "Admin Controller",
  "Vanish": "Vanish",
  "GodMode": "God",
  "Radar": "Radar",
  "AdminTP": "AdminTP"
}
```
## Credit
Thanks [@Speedy2M](https://oxidemod.org/members/speedy2m.57653/) for the logo

## Images
![Admin Panel](https://oxidemod.org/attachments/adminpanel-jpg.25449/ "Admin Panel")
