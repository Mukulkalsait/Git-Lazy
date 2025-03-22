╰─ git push

Enumerating objects: 31, done.
Counting objects: 100% (31/31), done.
Delta compression using up to 20 threads
Compressing objects: 100% (19/19), done.
Writing objects: 100% (20/20), 180.85 KiB | 18.08 MiB/s, done.
Total 20 (delta 9), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (9/9), completed with 7 local objects.

<!---G: 1st rename from git-hub .  -->
<!--   then we get this message at "PUSH" -->S

remote: This repository moved. Please use the new location:
remote: https://github.com/Mukulkalsait/2_rust-Programming.git

To https://github.com/Mukulkalsait/rust-Programming.git
5a209e3..5f2e1dd main -> main

<!-- Y: SOLUTION : -->

git remote set-url origin https://github.com/Mukulkalsait/2_rust-Programming.git

<!-- Y: verification : -->

╰─ git remote -v

origin https://github.com/Mukulkalsait/2_rust-Programming.git (fetch)  
origin https://github.com/Mukulkalsait/2_rust-Programming.git (push)

<!--DX: Done -->
