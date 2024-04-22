# Change Log

All notable changes to the "koffee-kreme" extension will be documented in this file.

## [Unreleased]

- Add other variants of theme to suite more light or dark styles, while still having good color contrast.

## [Fixed] ~ AchroDev 4/21/24 11:18 PM
- Fixed all titles in CHANGELOG having the strikethrough to being normal text.

## [Fixed] ~ AchroDev 4/21/24 11:06 PM
- Fixed typos in CHANGELOG.


## [Updated] ~ AchroDev 4/21/24 10:13 PM
- ```editorCodeLens.foreground``` was updated to ```#626262```
- ```sideBar.background``` was updated to ```#99806b```
- ```sideBarTitle.foreground``` was updated to ```#3d2a1c```
- ```list.highlightForeground``` was updated to ```#735641```
- ```input.placeholderForeground``` was updated to ```#5a5048```

## [Fixed] ~ AchroDev
- Fixed typos in README

## [Updated] ~ AchroDev 4/18/24
The following elements color have been updated to solve visibility issues and should have been transparent from the start.
- ```editor.selectionBackground``` was updated to ```#d5b69cbd```
- ```editor.inactiveSelectionBackground``` was updated to ```#bca4917e```
- ```editor.selectionHighlightBackground``` was updated to ```#cbac94d1```
- ```editor.rangeHighlightBorder``` was updated to ```#d2c7bf66```
- ```diffEditor.insertedTextBackground``` was update to ```#a5ee9448```
- ```diffEditor.removedTextBackground``` was updated to ```#d9858358```
- ```merge.currentHeaderBackground``` was updated to ```#a4e3d69d```
- ```merge.currentContentBackground``` was updated to ```#dbf4efb5```
- ```merge.incomingHeaderBackground``` was updated to ```#a6cfffbf```
- ```merge.incomingContentBackground``` was updated to ```#dbecff78```
- ```merge.commonHeaderBackground``` was updated to ```#bfbfbf93```
- ```merge.commonContentBackground``` was updated to ```#e5e5e568```
- ```minimap.findMatchHighlight``` was updated to ```#b5a39660```
- ```minimap.selectionHighlight``` was updated to ```#90776260```

The following elements fontStyle have been updated to the needed style.
- ```entity.other.attribute-name.id``` was updated to ```italic``` fontStyle
- ```entity.other.attribute-name.class.css``` was updated to ```italic``` fontStyle

Fixed some typos in the README

**Please submit an issue if you have any trouble with seeing any element in VS Code.**

## [Updated] ~ AchroDev 4/18/24
- Updated theme backup file

## [Added] ~ AchroDev - 4/14/24
- Installation instructions for anyone who visits the GitHub first and doesn't wish to visit the marketplace.
- Added version badge to README
- Added some extra touches to the overall look of the README and CHANGELOG

## [Changed] ~ AchroDev - 4/14/24
- Updated ko-fi button to HTML code with png instead of using the Markdown syntax as the image was unreasonably large.

## [Changed] ~ AchroDev - 4/6/24
- Donate button was not accepted from ko-fi as an svg, updated to use a png version.

## [Fixed] ~ AchroDev - 4/6/24

- Fixed the package.json from reading the ("vscode": "^1.17.0") as ("vscode": "^1.88.0") due to me misunderstanding the compatibility. All vscode editors 1.17 and up should now be able to install the extension.