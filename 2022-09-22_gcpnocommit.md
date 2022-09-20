We can cherry-pick the content of a commit without actually commit it

```bash
git cherry-pick --no-commit <ref>
# or
git cherry-pick -n <ref>
```

I was previously doing

```bash
git cherry-pick <ref>
git reset HEAD~1 --soft
```
