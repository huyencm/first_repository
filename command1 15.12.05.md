git status と git diff の実行結果

```bash
On branch main
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   .DS_Store
	deleted:    Readme.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	huyen/Readme.md
	huyen/command1.md

no changes added to commit (use "git add" and/or "git commit -a")
---GIT_DIFF_START---
diff --git a/.DS_Store b/.DS_Store
index a346c9d..cf6806c 100644
Binary files a/.DS_Store and b/.DS_Store differ
diff --git a/Readme.md b/Readme.md
deleted file mode 100644
index 78fdbe3..0000000
--- a/Readme.md
+++ /dev/null
@@ -1 +0,0 @@
-研修で作りました

```
