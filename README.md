# sed tips

  sed -e 's/^\([[:digit:]\{1\}]\)\([[:digit:]\+]\)\(.*\)$/mv "\0" "2\2\3"/' | bash
