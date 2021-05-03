# Streams API

- This module created by me is about Streams API introduced after JAVA 8. I have learnt and Practiced the Usecase Examples and I find it very useful also for my friends, so i have added the contents in this public repository.

# Java 8 Stream API

- A Stream in Java 8 can be defined as a sequence of elements from a source. Streams supports aggregate operations on the elements. The source of elements here refers to a Collection or Array that provides data to the Stream.

- Stream keeps the ordering of the elements the same as the ordering in the source. The aggregate operations are operations that allow us to express common manipulations on stream elements quickly and clearly.

# Java Stream vs Collection

- A Collection is an in-memory data structure, which holds all the values that the data structure currently has. Every element in the Collection has to be computed before it can be added to the Collection. While a Stream is a conceptually a pipeline, in which elements are computed on demand.

- The idea is that a user will extract only the values they require from a Stream, and these elements are only produced—invisibly to the user—as and when required. This is a form of a producer-consumer relationship.

- In Java, java.util.Stream represents a stream on which one or more operations can be performed. Stream operations are either intermediate or terminal.

- The terminal operations return a result of a certain type and intermediate operations return the stream itself so we can chain multiple methods in a row to perform the operation in multiple steps.

- Streams are created on a source, e.g. a java.util.Collection like List or Set. The Map is not supported directly, we can create stream of map keys, values or entries.

- Stream operations can either be executed sequentially or parallel. when performed parallelly, it is called a parallel stream.

- Based on the above points, if we list down the various characteristics of Stream, they will be as follows:

 1) Not a data structure
 2) Designed for lambdas
 3) Do not support indexed access
 4) Can easily be aggregated as arrays or lists
 5) Lazy access supported
 6) Parallelizable
