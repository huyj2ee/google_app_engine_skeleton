The skeleton could be upgraded to some simple utilities via their patch files
in this folder. Use below command to upgrade:
    git apply name-of-patch-file.patch

The patch files list are:
1. 0001-App-upgrade-project-with-utility-Unicode-format-conv.patch
  . An utility support render text in bold or italic by convert the normal text
    into corespondance codepoint of the bold or italic one.
  . This allows a pure text (eg. text edited by notepad++) could be formated
    bold or italic
