Features of Java Stream
A stream is not a data structure instead it takes input from the Collections, Arrays, or I/O channels.
Streams don’t change the original data structure, they only provide the result as per the pipelined methods.
Each intermediate operation is lazily executed and returns a stream as a result, hence various intermediate operations can be pipelined. Terminal operations mark the end of the stream and return the result.
Before moving ahead in the concept consider an example in which we are having ArrayList of integers, and we suppose we apply a filter to get only even numbers from the object inserted.

How does Stream Work Internally?
In streams,

To filter out from the objects we do have a function named filter()
To impose a condition we do have a logic of predicate which is nothing but a functional interface. Here function interface can be replaced by a random expression. Hence, we can directly impose the condition check-in our predicate.
To collect elements we will be using Collectors.toList() to collect all the required elements.
Lastly, we will store these elements in a List and display the outputs on the console.

