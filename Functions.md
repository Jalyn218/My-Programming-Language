Again, functions work similar to how they do in python except they are defined with the 'function' keyword instead of 'def' and require an 'end' instead of indentation.
### Defining functions
```text 
var result

function add(a,b) >> defining function with name 'add' and parameters a and b
	result = a + b
end
```

### Calling functions
```text 
add(3,5) >> calling add function with arguments passed in
display(result)
```

### Using the return keywords
In the example above, we create a variable to store our result in before calling the function but this is a terrible way to do it, so, just like in Python, the ``` return ``` keyword can be used.

```text 
function add(a,b):
	return a + b
end

result = add(3,5)
display(result)
```