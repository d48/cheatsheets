### Go to closing curly brace
  
	// place cursor over opening or closing curly brace
	%
  

## align markdown table

```bash
<leader>\t|
```

## surround plugin - word

```bash
# surround string with a character.
# mnemonic: 'c'hange 's'urrounding 'w'ith (some character)
<cursoronstring> csw'  

# wraps cursoronstring with `'` character
```

## surround plugin - change character with another charcter

```bash
# mnemonic - 'c'hange 's'urrounding "-character with '-character
<place cursor inside quoted string>cs"`

# "hello world" will change to `hello world`
```

## surround plugin - multiple words

```
# mnemonic: 'v'isually select and 'S'urround 'some character'
v<selectwords>S"

# wraps selectedwords with `"` character
```

## Align

```
v<selectmultiplellines>:Align {

# aligns all text on each row to the '{' character

v<selectmultiplellines>:Align { -

# aligns all text on each row to the '{' character, and then the '-' character
```


## Comment lines with motion using t-Comment

```
# mnemonic: 'g'o 'c'omment '4'lines j-down
gc4j

# comments out lines from current line to 4 down
```

## Count number of matching pattern in current file

```
:%s/mypattern//gn

## outputs number of matches
```

## align markdown table

```bash
<leader>\t|
```

## surround plugin - word

```bash
# surround string with a character.
# mnemonic: 'c'hange 's'urrounding 'w'ith (some character)
<cursoronstring> csw'  

# wraps cursoronstring with `'` character
```

## surround plugin - change character with another charcter

```bash
# mnemonic - 'c'hange 's'urrounding "-character with '-character
<place cursor inside quoted string>cs"`

# "hello world" will change to `hello world`
```

## surround plugin - multiple words

```
# mnemonic: 'v'isually select and 'S'urround 'some character'
v<selectwords>S"

# wraps selectedwords with `"` character
```

## Align

```
v<selectmultiplellines>:Align {

# aligns all text on each row to the '{' character

v<selectmultiplellines>:Align { -

# aligns all text on each row to the '{' character, and then the '-' character
```


## Comment lines with motion using t-Comment

```
# mnemonic: 'g'o 'c'omment '4'lines j-down
gc4j

# comments out lines from current line to 4 down
```

## Count number of matching pattern in current file

```
:%s/mypattern//gn

## outputs number of matches
```

## Increment number on under cursor

```
<ctrl>+a to increment
<ctrl>+x to decrement
```

## mark and copy and paste 
```
mk // mark spot as k
y'k // yank lines into spot k
p // paste that bad boy
```

