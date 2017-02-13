This is package sed of Shinyshell.

This package contains the following functions:

$ sed  : ""

$ search_and_replace  : "(Note: This sed command matches a search pattern X and replace it with pattern Y). Arguments of this function are given like this: search_and_replace DESCRIPTION1 REGEXP1 DESCRIPTION2 REGEXP2 ... REPLACE_PATTERN You can give as many groups of DESCRIPTION REGEXP as you want. The regexps will all be concatenated to become the search pattern. (Descriptions are only here for readability purpose) Example: search_and_replace ANY ".*" WORD_WITHOUT_SLASH "[^ /]*" SLASH '/' END_OF_LINE '.*' 'Replacement_text' Important note: If your description starts with '__', the following regexp is a capturing group, that you can recall in the REPLACE_PATTERN: Example: search_and_replace ANY ".*" __WORD_WITHOUT_SLASH "[^ /]*" SLASH '/' END_OF_LINE '.*' 'Word without slash: \1'"

$ str_delete  : ""

