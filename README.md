## Building a REST Async API with Akka

The main goal for this post is to desgin and build a asynchronous operations RESTFull API using Akka. The main motivation to write this article is to answer the question:
  - How I run long opeations without blocking my Client through RESTfull?
That is a problem tha I can not just solve this problem with different concurrency model like an actor model or an event bus (with RxJava). Also, this different than run asynchronous requests in backgroud which is most of Async HTTP-Servers does today, which is really good to increase thorughput for IO intencive APIs.
if you want to make this API secury, whait for the [this article](http://As part of this Article I will show how make it secury with JWT).

So lets start code

### Setting up your project

´´´scala
def test()

