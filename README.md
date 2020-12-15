# wtl-account-css

**Working with tags**
List of releases can be found there https://github.com/jsmbars/wtl-account-css/releases

Tags naming convention:
* We use only major numbers for css releases.
* `v*-release` - release tag, used for merge commits (* - is a release number)
* `v*-fixes` - hotfixes tag, used for commits that were pushed directly to master (* - is a release number)

Checking tags from local repo:
1) `git ls-remote --tags` - will show list of remote tags
2) `git tag` - will show list of local tags
3) `git describe --abbrev=0 --tags` - will show current local tag

Creating tags:
1) Merge feature-branch PR into master
2) In your local repo checkout master branch and pull the last changes (with merge commit)
3) Add local tag `git tag tagname`
4) Push tag to remote repo `git push origin tagname`
