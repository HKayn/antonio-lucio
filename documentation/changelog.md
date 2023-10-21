# Changelog

## v1.1.0 (2023-10-21)

### Changes

- The bookmark bar is now positioned between the address bar and the tab bar by default. Thanks [tojaroslaw](https://github.com/tojaroslaw) for suggesting this!
- The Command Chain Flag `al-disable-bookmarkbar-over-tabbar` is now available to revert this bookmark bar placement.
- Items inside the bookmark bar are now centered.
  - *This change is inspired by the centered position of the favorites bar in Safari.*
- The Command Chain Flag `al-disable-bookmarkbar-center-display` is now available to revert this behavior.
- Documentation has been updated and simplified.
- The demo image has been updated.

### Fixes

- The menu button is no longer partially covered; changes to the menu button width are now taken into account.
- When the window is not maximized, the menu button will no longer be vertically misplaced.
- Tab titles are now horizontally centered inside their tab once again.
- The stack counter is now vertically centered inside the tab.

### Known Issues

- When "Menu Position" is set to "Horizontal", the horizontal menu will be covered by the address bar.
- When "Use Native Window" is enabled, the address bar will still leave a gap for nonexistent window buttons.

---

## v1.0.4 (2023-10-14)

### Fixes

- Fixed several text elements not being correctly aligned.
- Fixed position of "Synced Tabs" and "Show Closed Tabs" buttons.

---

## v1.0.3 (2023-04-23)

### Fixes

- Tab stack borders are no longer taller than the tab.
- Compact tab stacks no longer introduce an unnecessary gap above the tab bar.

---

## v1.0.2 (2023-04-23)

### Fixes

- Styles are no longer being applied while in fullscreen.

---

## v1.0.1 (2023-04-20)

### Fixes

- Styles are no longer being applied to the settings page.

---

## v1.0.0 (2023-04-20)

First release of Antonio Lucio.
