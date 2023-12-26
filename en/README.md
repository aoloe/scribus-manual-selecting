# Selecting items in Scribus

__Draft__: This document is an early draft.  

## Using the "Select Item" tool

You can always select items with the arrow (the Select tool).  
Click on the "Arrow" tool in the toolbar to enable it.

If you are editing some text or in other _edit modes_ (like moving an image inside of the frame, you can use the Esc key to get _back_ into the "Select Item" mode.  
You can then select other items as if you had s.

## Selecting other items while in _edit mode_

When you're in edit mode, you can also click on other shapes.

What exactly happens, depends on the type of the origin and target items. The target will at least be selected. Sometimes directly set in edit mode.

This is mostly useful when you're editing some text and you want to continue the editing on a different text frame: you can click on a specific position in the target frame and continue the editing from there.  
You can even start a new selection.

## Selecting text

- shift key to extend the selection to the cursor place
- it is not currently possible to accross the frame boundary. For such cases you can use the story editor to select a the text as you wish and apply a limited set of actions to it.

## Selecting multiple items

- Adding and removing items to the selection
- Using the mouse cursor to select all items inside of the select area. The start of the selection must always be on a point where there is no item.
- Using the cursor with the alt key to select the items touched by the selection area

## Selecting items hidden behind other items

By holding the ctrl key (cmd on a Mac) you can _cycle_ among the items that are under the cursor.

Sometimes, items are -- completely partially -- _stacked_ upon each other and if you want to activate one of the _lower_ items you need to press the ctrl key to _reach_ them.  
If you're used to double click on an item to get into its edit mode, you can _obviously_ not do that for the lower items. In such a case you can use the E key (without any modifier) to activate the edit mode and start editing the frame.

Example can be:

- Moving the image inside of a frame that is placed as a background behind some text.
- TODO: find a good example where the test is behind

TODO: add an animated gif.

## Grouping items

Sometimes you want to _keep_ a selection: then you can group the select items.

For grouping the selected items, you can use the `ctrl-g` keyboard shortcut (`cmd-g` on Mac) or with _Item > Grouping > Group_.

There are then many actions that you apply to the the group, as if they were one single item (as an example for moving it around).

The group can be released with the `ctrl-shift-g` keyboard shortcut (`cmd-shift-g` on a Mac) or with _Item > Grouping > Ungroup_.

## Selecting items inside of groups

If you want to select an item inside of a group you can press the alt key and click on the specific frame.

You can combine the ctrl and alt keys to select items in the group that are behind other items

## Selecting items on a different layer

If you create multiple layers, by default you can only select items that are on the active layers.

This is what most users want in the typical case.

For the case when you want to enable the selection of items on a specific layer, while other layers are active, you can activate "Select Objects on Layer" for that layer.

TODO: screenshot of the layers palette (and possibly a gif showing how it works)

## Using the _Outline palette_

## Naming items

For very special cases, it might be useful to give a specific name to an item, and make it easier to select it.  
As an example by making it stand out in the outline palette.

Also [a script exists](https://github.com/aoloe/scribus-script-repository/tree/master/search-by-item-name) that helps you selecting an item by its name.
