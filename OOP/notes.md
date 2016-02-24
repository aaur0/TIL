### constructor

The rule of thumb is, don't introduce a new attribute outside of the __init__ method, otherwise you've given the caller an object that isn't fully initialized. There are exceptions, of course, but it's a good principle to keep in mind. This is part of a larger concept of object consistency: there shouldn't be any series of method calls that can result in the object entering a state that doesn't make sense.


