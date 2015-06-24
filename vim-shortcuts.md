# selection
* viB - select everything inside { } tags
## movement
* `ci<tag>` select delete and go to insert mode between tags - ci" will select all text within quote
* `vi<tag>` just select 
* `0dg` - delete from beginning of current line to end of the file
* `cw` - change to end of word

# navigation
* `gg/G` - to bottom/to top of file 
* `mx` - set mark for x (being a-zA-Z)
* `'x` - goto mark x
* `` `V/\`\`\`bb` `` - select rest of code in Rmd chunk
* `A/I` - go to end/beginning of line and enter insert mode

# replacement
visual replace - s/<existing>/<replacement>

# organization
## splits
:vsp - vertical split
:sp - horizontal split

:10sp <filename> - specify split height and what file to open
## more info https://robots.thoughtbot.com/vim-splits-move-faster-and-more-naturally


