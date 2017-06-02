# Setup Instructions
`brew install glib ncurses gtk`

# Build Instructions
1) `hg clone https://foicica.com/hg/textadept`
2) `cd src`
3) `make osx-deps`
4) `patch -p2 < build.patch`
5) `make osx-curses`
6) `../textadept-curses`

# Notes
Tested on macOS Sierra. Textadept repo revision: changeset 2329:90d027eb635f
