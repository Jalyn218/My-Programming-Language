This section contains for loops and while loops. Much like if statements, loops require the 'end' keyword, parentheses around expressions and no indentation.
### For loops
Unlike Python, for loops in my language are inclusive at both ends.
```text
count [variable] from [start] to [end]
	>> CODE
end
```

```text 
count i from 1 to 5 >> INCLUSIVE
	display(i)
end

>>>>>>>>>>>>>>>>>>>>>OR>>>>>>>>>>>>>>>>>>>>>>>>>>

count i from 0 to 10 using 2 >> 0, 2, 4, 6, 8, 10
	display(i)
end
```
### While loops
```text 
var number = 10

while(number > 2)
	display(number)
	number = number - 1
end
```