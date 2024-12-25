### Changing column of text

Suppose there is this text:

```css
li.one   a{ background-image: url('/components/sprite.png'); }
li.two   a{ background-image: url('/components/sprite.png'); }
li.three a{ background-image: url('/components/sprite.png'); }
```

Change 'images' to 'components' to look like this:

```css
li.one   a{ background-image: url('/components/sprite.png'); }
li.two   a{ background-image: url('/components/sprite.png'); }
li.three a{ background-image: url('/components/sprite.png'); }
```

Steps to get there:

`<C-v>jje` - visual select the entire block <!-- BUG: I have to do C-V (i.e. 
C-S-v), with different results: why?-->
`c` - change the selection
`components` - type in the text 'components'
`<Esc>` - add the word 'components' to the other lines
Note, `<C-c>` is not `<Esc>` :-(