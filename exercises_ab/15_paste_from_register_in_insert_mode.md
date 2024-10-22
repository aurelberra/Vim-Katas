### Paste from register in insert mode

Here is an unfinished excerpt of text:

```text
Practical Vim, by Drew Neil
Read Drew Neil's Practical Vim
```

Copy and paste the page title here:

`yt,` - yanks the text 'Practical Vim
`jA` - jumps to the end of the second line and adds a space <!-- HACK: good 
habit -->
`<C-r>0` - pastes the text from register <!-- HACK: practice! -->
`.<Esc>` - adds the dot to the very end

Make it look like this:

```text
Practical Vim, by Drew Neil
Read Drew Neil's Practical Vim.
```
