
    [user]
        name = Xu Jun
        email = jun.xu.falcon@gmail.com

    [core]
        editor = vim

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

    [commit]
    #template = ~/.gitcm.template

    [credential]
        helper = cache --timeout=3600
        #use git credential-cache exit; to clean cached userpwd.
        helper = store --file=~/.gitpassword
        #will use that file to store.
