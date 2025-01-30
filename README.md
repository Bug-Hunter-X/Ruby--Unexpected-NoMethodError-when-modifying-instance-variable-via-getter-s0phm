# Ruby: Unexpected NoMethodError when modifying instance variable via getter

This example demonstrates a common error in Ruby where attempting to modify an instance variable directly through the getter method throws a `NoMethodError`. The getter method only returns the value; it does not allow modification.

To solve this, explicit setter methods must be defined.
