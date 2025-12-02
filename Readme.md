# simplerc 🎈

load minimal config on remote server with 
`source <(curl -sL https://raw.github.com/luisbecker-gh/simplerc/main/.simplerc)`

or 

`tmpfile=$(mktemp) && \
curl -sL https://raw.github.com/luisbecker-gh/simplerc/main/.simplerc -o "$tmpfile" && \
source "$tmpfile" && \
rm "$tmpfile"`
