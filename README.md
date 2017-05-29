# Setup Instructions
brew install glib ncurses gtk

# Build Instructions
1) Clone the repo, https://foicica.com/hg/textadept
2) Apply build.patch
3) Run `export PKG_CONFIG_PATH=/usr/local/opt/ncurses/lib/pkgconfig`
4) Run `make osx-curses`
5) Run `textadept-curses`

# Notes
Tested on macOS Sierra. Textadept repo revision: changeset 2329:90d027eb635f
