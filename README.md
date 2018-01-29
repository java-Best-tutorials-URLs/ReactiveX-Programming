# ReactiveX-Programming
https://github.com/ReactiveX/RxJava#version-1x-javadoc </br>
<h2>Version 1.x (Javadoc) </h2>

Looking for version 1.x? Jump to the 1.x branch.
Timeline plans for the 1.x line:
June 1, 2017 - feature freeze (no new operators), only bugfixes
March 31, 2018 - end of life, no further development

<h2>Version 2.x (Javadoc) </h2>

single dependency: Reactive-Streams
continued support for Java 6+ & Android 2.3+
performance gains through design changes learned through the 1.x cycle and through Reactive-Streams-Commons research project.
Java 8 lambda-friendly API
non-opinionated about source of concurrency (threads, pools, event loops, fibers, actors, etc)
async or synchronous execution
virtual time and schedulers for parameterized concurrency

<h2>RxJava is a Java VM implementation of Reactive Extensions.</h2>

Question arises in mind, What is Reactive Extensions?

From the official doc, Reactive Extensions(ReactiveX) is as a library for composing asynchronous and event-based programs
by using observable sequences.

Now we have to learn these three terms - asynchronous, event-based and observable sequences.

Asynchronous: Different parts of the program run simultaneously.
Event-Based: The program executes the code based on the event generated.
Observable Sequences: We will see it later for better understanding.
The Reactive Extension is further elaborated: It extends the observer pattern to support sequences of data and/or events
and adds operators that allow you to compose sequences together declaratively while abstracting away concerns about things
like low-level threading, synchronization, thread-safety, concurrent data structures, and non-blocking I/O.

All components are as follows:

Flowable, Observable, Single, and Completable - does some work and emit values.
Subsciption - work is going on or completed or is used to cancel.
Operators - Modify Data
Schedulers - Where the work should be done, which thread like main thread, etc.
Subscriber/Disposable - where the response will be sent after work has been completed.


http://www.vogella.com/tutorials/RxJava/article.html </br> 
http://www.baeldung.com/rxjava-tutorial </br>
http://www.baeldung.com/rx-java </br>
https://blogs.oracle.com/pavelbucek/jax-rs-21-reactive-client-api </br>
https://github.com/shamoh/jersey--examples--rx-client-java8-webapp </br>
https://examples.javacodegeeks.com/core-java/reactive-java-rxjava-tutorial-introduction/ </br>
https://medium.com/@milenko_52829/understanding-java-rxjava-for-beginners-5eacb8de12ca </br>
http://www.baeldung.com/rxjava-testing </br>


