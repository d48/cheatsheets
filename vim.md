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
