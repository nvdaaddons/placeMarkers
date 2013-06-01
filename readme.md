﻿[[!meta title="placeMarkers 1.0"]]

# placeMarkers 1.0 #

It is to be used for saving and searching specific text strings or bookmarks, on web pages or documents in NVDA's brouse mode. 
The plugin saves the specified strings and bookmarks to text and pickle files. The name of these files is based on the title and URL of the current document.

This addon is based on SpecificSearch and Bookmark&Search, developed by the same author. You should uninstall them to use this one, since they have common keystrokes and features.

## Key Commands: ##

*	control+shift+NVDA+s; Opens a dialog for saving a string of text that you may wish to find on the current document. By default it shows the text previously saved for this file. If this text is deleted, the text file containing the corresponding string will be also removed.
*	control+shift+NVDA+f; If the current document has a text file for specific search, opens a dialog that shows the saved string of text. When you press OK, NVDA search for the text set on the dialog edit box. If no text file is found for this document, NVDA announces it without opening Specific Search dialog.
*	control+shift+NVDA+k; Saves the current position as a bookmark
*	control+shift+NVDA+delete; Deletes the bookmark corresponding to this position.
*	control+shift+k; Moves to the next bookmark.
*	shift+NVDA+k; Moves to the previous bookmark.
*	NVDA+k; Copies to clipboard the file name, without extension, where could be saved place markers (positions or a string to search).

## Place markers Submenu (NVDA+N) ##

Using Place markers submenu, under Preferences menu, you can access to 

*	Specific search folder: opens a folder of specific searches previously saved.
*	Bookmarks folder; opens a folder of the bookmarks saved.
*	Copy placeMarkers folder; you can save a copy of the bookmarks folder.
*	Restore placeMarkers; you can restore your bookmarks from a placeMarkers folder previously saved.
*	Documentation file, in your selected language if available, or English by default.

Note: The bookmark position is based on the number of characters; in pages with a dynamic content is better to use the specific search, and not the bookmarks to save a precise position.

