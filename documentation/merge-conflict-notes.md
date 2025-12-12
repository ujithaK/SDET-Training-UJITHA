# Merge Conflict Notes – index.html

## 1. What Caused the Conflict?

A merge conflict occurred while merging **feature/python-basics** into **main**.

Both branches modified the same section inside **index.html**, specifically the
HTML `<body>` area where headings and content lines were changed.

Git could not automatically decide which version to keep because:

- **feature/python-basics** added:


## 2. How the Conflict Was Resolved

1. Opened the Pull Request conflict screen on GitHub.
2. Reviewed both versions of the conflicting section in `index.html`.
3. Chose **“Accept both changes”** to combine content from both branches.
4. Manually cleaned up the merged HTML to ensure proper structure and formatting.
5. Clicked **“Mark as resolved”** in GitHub.
6. Committed the merge resolution to complete the process.

## Final Result

Pull request successfully merged and closed
