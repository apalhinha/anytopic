---
title: Pattern for Error Handling in Java
---
# Principles

* At high-level, errors are innocuous. Worst case scenario nothing happened and the user can try again.
* The lowest level will show the stack-dump, not others.
* TODO: After an error, the upper levels should display their context information in a nicer format

# Top level, where errors are innocuous
At top level an error keeps the user state as it was before.
The user will decide whether to retry, or quit.

```java
	public void toplevel() {
		// Acts as the top level for the error handler, no more throws from here
		try {
			do_something();
		} catch (Exception e) {}
		return ;
	}
```

# Inner level, log stack and context
