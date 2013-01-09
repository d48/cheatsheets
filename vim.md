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
# mnemonic: 'c'hange 's'urrouning 'w'ith (some character)
<cursoronstring> csw'  

# wraps cursoronstring with `'` character
```

## surround plugin - multiple words

```
v<selectwords>S"

# wraps selectedwordsw with `"` character
```

## Align

```
v<selectmultiplellines>:Align {

# aligns all text on each row to the '{' character

v<selectmultiplellines>:Align { -

# aligns all text on each row to the '{' character, and then the '-' character
```
