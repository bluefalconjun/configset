
[user]
    name = Xu Jun
    email = jun.xu.falcon@gmail.com
[core]
    editor = vim
[commit]
    template = /$home/.gitcm.template
[help]
    autocorrect = 1
[color]
    ui = true
[color "diff"]
    meta = blue black bold
[alias]
    st = status
    lg = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
    br = branch
    cm = commit
    
[credential]
    helper = cache --timeout=3600000 //this is for github to record your username/pwd
    
    [url "ssh://username@192.168.100.10:29418"]
        insteadof = ssh://192.168.100.10



