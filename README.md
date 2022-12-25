# Git Tag Example
What is git tag?
git tags are ref's that point to specific points in Git history. Tagging is generally used to capture a point in history that is used for a marked version release (i.e. v1.0.1). A tag is like a branch that doesn’t change. Unlike branches, tags, after being created, have no further history of commits

For Example:

**Create Tag in git**:
```sh
$ git commit -m "v0.0.1 release" && git tag v0.0.1 && git push origin master --tags
```