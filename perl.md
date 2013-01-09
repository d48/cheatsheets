## To get match into a variable from condition statement

```perl
if('Quick brown fox' =~ /Quick (\w+)/g) {
	print "This is $1\n";
}
```
Output: "This is brown"
