Let's look at <i>Self-Encapsulation</i> using the example of a range class.<br/><br/>Self-encapsulation means implementing access to fields through access methods even in the methods of the class itself.

These access methods must be created if they do not yet exist. So go ahead and create getters and setters in our class.

Our example has several methods that use direct access to fields.

To finish self-encapsulation, let's replace all references to fields in these methods with getter and setter calls.

As you may have noticed, we did not touch the assignment in the constructor. It is often assumed that a setter is used after an object has already been created, so its behavior may be different than during initialization.

Let's start the final testing.

Now refactoring is complete. If you like, you can compare the old and new code.