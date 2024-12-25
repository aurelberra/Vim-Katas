### Running commands in shell

1. Combine two commands with one shell execution:

`:write !sh` - will write this file (a vim command) and start a shell

2. Sort the content of this text:

```
first name, last name, email
john,smith,john@example3.com
drew,neil,drew@vimcast1.org
drew,neil,drew@vimcast1.org
jane,doe,jane@example0.com
```

Visual highlight the lines to be sorted
`:'<,'>!sort -t',' -k2` - the sort shell command is used to sort the lines
<!-- HACK:simpler with default Vim implementation
* sort on chosen column: sort /.*\%2v/
* sort on first number: sort n
* sort unique: sort u
-->

3. Pull up command history in vim

`q:` will show normal mode history
`q/` will show search history
