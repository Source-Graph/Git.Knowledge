https://www.google.com/search?q=git+clone+continue+after+error

# Discuss:
https://stackoverflow.com/questions/3954852/how-to-complete-a-git-clone-for-a-big-project-on-an-unstable-connection
>Use shallow clone i.e. git clone --depth=1, then deepen this clone using git fetch --depth=N, with increasing N. You can use git fetch --unshallow (since 1.8.0.3) to download all remaining revisions.

# Php helper script:
https://superuser.com/questions/512190/does-git-clone-have-resume-capability
