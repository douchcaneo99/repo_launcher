1. "repo_launcher/system/bin/"
2.     mkdir ~system/bin
3. PATH=~system/bin:$PATH
4. curl https://storage.googleapis.com/git-repo
        -downloads/repo > ~system/bin/repo
   chmod a+x ~/bin/repo
5. gpg --recv-key 
6.     8BB9AD793E8E6153AF0F9A4416530D5E920F5C65
   curl https://storage.googleapis.com/git-repo
7.      -downloads/repo.asc | gpg --verify - ~system/bin
        /repo
