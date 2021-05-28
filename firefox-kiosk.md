# Firefox KIOSK Mode
## 28.05.2021r.

### about:config

```
browser.backspace_action 0
browser.bookmarks.restore_default_bookmarks false
browser.link.open_newwindow 1
browser.link.open_newwindow.override.external 1
browser.link.open_newwindow.restriction 0
browser.sessionstore.resume_from_crash false
toolkit.startup.max_resumed_crashes -1
```

### handy add-ons

```
AdGuard
Download Blocker
Popupblocker
```

Remeber to check preferences for your needs!

### creating and running firefox by profiles

to create:

```
firefox --no-remote -P
```

to run created profile in kiosk mode:

```
firefox --no-remote -P "profile_name" --kiosk
```
