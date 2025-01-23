# Unexpected Read-Only Behavior of Implicit Getters in Ruby

This repository demonstrates an uncommon error in Ruby related to the read-only nature of implicit getter methods.  While you can directly access instance variables like `@value`, you cannot directly assign to them like you would in many other object-oriented languages. Attempting to do so leads to a `NoMethodError`.

The `bug.rb` file shows the problematic code. The `bugSolution.rb` file presents a solution using explicit getter and setter methods.