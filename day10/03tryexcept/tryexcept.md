#
#Python Try Except

The  try  block lets you test a block of code for errors.

The  except  block lets you handle the error.

The  else  block lets you execute code when there is no error.

The  finally  block lets you execute code, regardless of the result of the try- and except blocks.


# Exception Handling
When an error occurs, or exception as we call it, Python will normally stop and generate an error message.

These exceptions can be handled using the try statement:
try:
  # tests a block of code that may cause errors
except Exception as e:
  # handles the error
else:
  # executed when there is no error
finally:
  # always executed, error or not



