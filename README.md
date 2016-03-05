# intro to git and go

NOTE: I recommend installing all software to their default directories on Windows or Mac

install git {
    https://git-scm.com/downloads
    just install the plain git, no GUIs

    this is a version control system that \
    allows simple control of your source \
    code through a push/pull mechanism
}

create github account {
    optional but *highly* recommended

    this is a website that acts as a \
    simple web storage system for your \
    git repos
}

install gitkraken {
    http://www.gitkraken.com/

    LUXURIOUS gui for git on all platforms
    OPTIONAL: you will definitely want this later though
}

install go {
    https://golang.org/dl/

    modern replacement for C/C++ courtesy \
    of your benevolent overlords at Google
}

install atom {
    https://atom.io/

    source editor written in HTML/CSS3/Node.js
    OPTIONAL: but totally awesome
}

create directory {
    I recommend using something like C:\dev\ for \
    all dev work, with subdirectories like \go\example\
}

right click in a folder titled example to open \
a git BASH in that folder; then do

commands {
    git init
    git remote add -m example https://github.com/matthewmahoneyms/example.git
    git pull example master
}

then drag that example folder into Atom for maximum ease
