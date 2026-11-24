# vocabs-main
Deyploment for the different versions of ACDH-CH vocabs based upon the branch. The `main`-branch is the default one, where every change should be put at first. There is no action bound to the `main`-branch. After changes pushed to `main`, there should be a merge to the branch, where an update should be run. This will then trigger the action.

Remarks:
* the config.ttl-file to copy for Skosmos depends on the branch where you push, e.g. pushing to `prod` takes the config_production.ttl
* to update the submodule of Skosmos, run `git submodule update --remote --merge` 
