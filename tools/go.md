-----
 - download go src from github.

         git clone https://github.com/golang/go  #source code
         or
         wget https://storage.googleapis.com/golang/go1.7.3.linux-amd64.tar.gz  #binary release

-----
 - set go root env in bashrc

        export GOROOT=/home/usr/bin/go
        export PATH=$PATH:$GOROOT/bin


**note GOROOT is NOT GOPATH, GOROOT contains system and GOPATH contains usr data.**

-----
 - set go path env in bashrc

        export GOPATH=$HOME/workspace/go
        export PATH=$PATH:$GOPATH/bin

 - go path folder structure
        bin/
            hello                          # command executable
            outyet                         # command executable
        pkg/
            linux_amd64/
            github.com/golang/example/
                stringutil.a           # package object
        src/
            github.com/golang/example/
                .git/                      # Git repository metadata
                hello/
                    hello.go               # command source
                outyet/
                    main.go                # command source
                    main_test.go           # test source
                stringutil/
                    reverse.go             # package source
                    reverse_test.go        # test source
            golang.org/x/image/
                .git/                      # Git repository metadata
                bmp/
                    reader.go              # package source
                    writer.go              # package source
        ... (many more repositories and packages omitted) ...
