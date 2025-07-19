---
## ExceptionHandling
 -Python Exception Handling handles errors that occur during the execution of a program. Exception handling allows to respond to the error, instead of crashing the running program.
 -Python uses `try`, `except`, `else`, and `finally` blocks to handle exceptions.
---

## Why Exception Handling?

- Prevents program crashes.
- Helps in debugging by catching specific errors.
- Improves user experience by providing meaningful error messages.
- Enables clean-up actions with `finally`.

---

## Basic Syntax

```python
try:
    # Code that might raise an exception
except SomeException as e:
    # Handle exception
else:
    # Runs if no exception occurs
finally:
    # Runs no matter what
---

## Common Exception Types
-**Exception**: Base class for all built-in exceptions except system-exit exceptions.
- **ArithmeticError**: Base class for errors related to arithmetic operations.
- **ZeroDivisionError**: Raised when division or modulo by zero takes place.
- **OverflowError**: Raised when a calculation exceeds the maximum limit for a numeric type.
- **FloatingPointError**: Raised when a floating point operation fails.
- **ValueError**: Raised when a function receives an argument of the right type but inappropriate value.
- **TypeError**: Raised when an operation or function is applied to an object of inappropriate type.
- **IndexError**: Raised when a sequence subscript is out of range.
- **KeyError**: Raised when a dictionary key is not found.
- **NameError**: Raised when a local or global name is not found.
- **AttributeError**: Raised when an attribute reference or assignment fails.
- **ImportError**: Raised when an import statement fails to find the module or name.
- **ModuleNotFoundError**: Raised when a module could not be found.
- **FileNotFoundError**: Raised when a file or directory is requested but doesn’t exist.
- **IOError**: Raised when an I/O operation fails (alias of OSError).
- **OSError**: Raised for operating system-related errors.
- **StopIteration**: Raised to signal the end of an iterator.
- **RuntimeError**: Raised when an error doesn’t fall into any other category.
- **IndentationError**: Raised when indentation is not correct.
- **TabError**: Raised when indentation consists of inconsistent tabs and spaces.
- **SyntaxError**: Raised when the parser encounters a syntax error.
- **SystemExit**: Raised by the sys.exit() function.
- **KeyboardInterrupt**: Raised when the user interrupts program execution, usually by pressing Ctrl+C.
- **MemoryError**: Raised when an operation runs out of memory.
- **StandardError**: predefined keywords mismatch
