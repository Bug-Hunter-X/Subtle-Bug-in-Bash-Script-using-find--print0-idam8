# Shell Script Bug: Incorrect Loop Condition with find -print0

This repository demonstrates a subtle bug in a bash script that uses `find -print0` to process files. The bug lies in the loop condition used to iterate over the null-separated file list.  The incorrect condition leads to incomplete processing or unexpected behavior.

The `bug.sh` file contains the buggy code. The `bugSolution.sh` file provides the corrected version.  The bug is described in more detail in the `bug.sh` file itself.