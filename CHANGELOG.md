## Next (0.0.20)

## 0.0.19

- Stats panel moved to the top right corner

## 0.0.18

- Fixed ObjectsTree's items is always unfolded by default. If item contains only one child unfold until find item with more than one children.
- Fixed selecting object now scrolls ObjectsTree to the center of list
- Updated "Plans" button - it is hidden when has not blueprints
- Fixed select objects on 2D was broken
- Updated cursor behavior - when we choose `comments` tool then measurements becomes none-interative.
- Renamed `Object Info` window to `Details`
- Fixed click on button details and focus now selects object
- Updated colors for measure samples. Now `angle`, `distance` and `mindistance` have different colors.
- Added highlighting effect for measure samples on hover
- Added shortcut `Shift + R` for `mindistance` tool
- Added IV Stats extension by default
- Added button in visibility settings to show Stats extension
- Fixed blueprints filter
- Fixed scrollbar
- Attributes now change in the window when another object has been selected
- Added `Minimum distance` measure sub-tool for finding minimum distance between objects
- Updated colors for measure samples. Now `angle`, `distance` and `mindistance` have different colors
- Added shortcut `Shift + R` for `mindistance` tool
- Added highlighting effect for measure samples on hover
- Added transparency effect for measure samples when create new sample or drag point
- Added selection of objects related to their measure samples. Objects will be painted with color of selected measure sub-tool

## 0.0.17 [DEPRECATED]

## 0.0.16

- Updated industrial-viewer
- Added chunks loading progress
- Added context menu

## 0.0.15

- UI improvements
- Updated presets background settings
- Updated presets ghostMode settings (except default)

## 0.0.14

- Fix scroll on select with collapsed nodes in object tree
- Make version button non interactive if `onOpenVersions` or `versions` not set

## 0.0.13

- Fix `logo` hover effect

## 0.0.12

- Change `logo` API

## 0.0.11

- UI improvements
- Added share button
- Refactor TextArea to fr-ui-kit's TextField multiline
- Added `logo` option

## 0.0.10

- Fixed `ResizeObserver loop limit exceeded` error spamming in Sentry extension

## 0.0.9

- UI improvements
- Added hierarchy support

## 0.0.8

- UI improvements
- Added the ability to cancel `measure` sample creation by pressing Esc keyboard button (IV-880)

## 0.0.7

- UI improvements
- Fix integration menu jump on progress state (IV-856)

## 0.0.6

- Added method `load` for file manifest loading
- `Settings.model` property doesn't accept string no more

## 0.0.5

- Updated UI style
- Added integration menu

## 0.0.3

- First working version
