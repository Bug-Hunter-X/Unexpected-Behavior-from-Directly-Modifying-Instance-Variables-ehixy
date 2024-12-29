# Unexpected Behavior from Directly Modifying Instance Variables in Ruby

This example demonstrates a potential issue in Ruby when directly modifying instance variables using `instance_variable_set` or `instance_variable_get`. While technically possible, this practice can lead to problems with encapsulation and make code harder to maintain.  It bypasses any access control or validation that might be implemented using accessor methods (getter and setter methods).

The `bug.rb` file showcases this. The `bugSolution.rb` offers a safer, more maintainable approach.