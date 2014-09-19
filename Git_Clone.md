##Explain what git clone does

Primarily, git clone duplicates the original git repository (origin) into a new directory.

It also:

* Creates remote tracking branches for each branch in the origin
* Creates and checks out a new 'initial' forked branch from the origin's active branch

The syntax to call git clone is:

$ git clone [url]

It has additional options including: -local, -quiet, -no-checkout


