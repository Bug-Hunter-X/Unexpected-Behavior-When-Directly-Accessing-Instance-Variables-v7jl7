# Unexpected Behavior When Directly Accessing Instance Variables in Ruby

This repository demonstrates a common, yet subtle, error in Ruby related to directly accessing and modifying instance variables outside of the class's defined methods.  While technically possible using `instance_variable_set` and `instance_variable_get`, this practice is generally discouraged. It can lead to difficult-to-debug issues and compromises the encapsulation of the class.

The `bug.rb` file showcases the problematic code, and `bugSolution.rb` presents a more robust solution.