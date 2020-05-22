# Introduction

This horizontal chooser widget for TiddlyWiki 5 is an animated chooser that stores the selected value when clicked. It allows selection options to be displayed on a horizontal line, and can be dragged to scroll when the options do not all fit within the visible element. 

This is really just a proof of concept, because (a) it relies on mouse events and does not work on touch interfaces, and (b) I'm sure it's an accessibility nightmare. I would guess that event handling would be easier to sort out than accessibility issues.

# Attributes

|Attribute |Description |
|--- |--- |
|items |String containing the items to select from, separated by spaces. In TiddlyWiki string-as-list style, surround items with spaces in their names with `[[` double square brackets `]]`. |
|title |Optional title of the tiddler to write the chosen item to (defaults to the current tiddler) |
|field |Optional field to write the chosen item to (defaults to "chooser_result") |
