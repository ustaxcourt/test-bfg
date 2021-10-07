# test-bfg

We are making this repo to help test BFG so that we ensure it's still usable by forked repositories trying to merge work in.

Here's what we're going to do:

- we'd need to make a repo
- make some commits in that repo with a fake api key
- put a 5meg file in there
- fork the repo
- remove the 5 meg file
- clean the repo up to remove blobs bigger than 1MB
- clean the repo up to remove the fake api key
- see how the forks can merge back into the main repository?
