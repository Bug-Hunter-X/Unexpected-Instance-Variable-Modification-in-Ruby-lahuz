# Unexpected Instance Variable Modification in Ruby

This repository demonstrates an uncommon Ruby bug related to directly modifying instance variables using `instance_variable_set`. While functional, this practice can lead to unexpected behavior and make code harder to maintain and debug.

The `bug.rb` file shows a simple class with an instance variable.  Direct modification via `instance_variable_set` bypasses typical access methods, which can make tracking changes more difficult.