gedit-c-symbol
==============

c symbol search for gedit

modification to /usr/libgedit/plugins/externaltools/functions.py
which gives external tools the current C like symbol under the cursor
as "GEDIT_CURRENT_SYMBOL" (also GEDIT_CURRENT_COLUMN_NUMBER to complete the
cursor position information)

useful for ad hoc programming assists like grep for definition
