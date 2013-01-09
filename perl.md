## To get match into a variable from condition statement

```perl
# places match from pattern inside parens into $1 variable
if('Quick brown fox' =~ /Quick (\w+) (\w+)/g) {
	print "This is $1\n";
	print "This is $2\n";
}
```
Output: 
This is brown
This is fox 
