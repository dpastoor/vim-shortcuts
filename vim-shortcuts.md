# selection
* viB - select everything inside { } tags
* vi{identifier} - select everything inside identifier (eg ), }, etc)
* ve - select inside word
    - in rstudio ve" will select and put quotes around a word
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
* f{char} - find next char
	* ; - go to next find occurance

vim stores a number of marks based on the last action

* `'[/]` - go to start/end of last change or yank    
* `'.` - location of last change
* `'>` - end of last visual selection

# replacement
visual replace - s/<existing>/<replacement>

# organization
## splits
:vsp - vertical split
:sp - horizontal split

:10sp <filename> - specify split height and what file to open
## more info https://robots.thoughtbot.com/vim-splits-move-faster-and-more-naturally


