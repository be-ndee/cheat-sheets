# Makefiles


```
 # file called 'Makefile'
 # aliases to use
 create_files:
 	touch foo
 	touch bar
 	touch foobar
 write_files:
 	echo "hello foo-world" > foo
 	echo "hello bar-world" > bar
 	echo "foo + bar = foobar" > foobar
 remove_files:
 	rm foo
 	rm bar
 	rm foobar
```

Calling the commands:  
` make create_files `  
` make write_files `  
` make remove_files `