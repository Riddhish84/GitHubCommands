# Setting Git Branch Sorting Criteria

```
git config --global branch.sort -committerdate
```

This command sets a new branch sorting criteria in the global Git configuration. By using the `-committerdate` option, it specifies to Git how branches should be sorted, based on "commiter date".

This means that branches will be ordered based on the date of their last commit. In other words, branches with the oldest commit date will be listed first, and those with the most recent commit date will be listed last.
