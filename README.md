# efterjul


[color]
        vi = true
[alias]
        st = status
        co = checkout
        ci = commit
        br = branch
        df = diff
        dfs = diff --staged
        logg = log --graph --decorate --oneline --abbrev-commit --all
[difftool "sourcetree"]
        cmd = opendiff \"$LOCAL\" \"$REMOTE\"
        path = 
[mergetool "sourcetree"]
        cmd = /Applications/Sourcetree.app/Contents/Resources/opendiff-w.sh \"$LOCAL\" \"$REMOTE\" -ancestor \"$BASE\" -merge \"$MERGED\"
        trustExitCode = true
.gitconfig (END)


