## Building a Async REST API with Akka HTTP

The main goal for this post is to desgin and build a asynchronous operations RESTFull API using Akka. The main motivation to write this article is to answer the question:
  - How I run long opeations without blocking my Client through a RESTfull API?

It is a problem that can not just be solved with different concurrency model like Akka actor model or an event bus (with RxJava). This different than run asynchronous requests in backgroud, which is most of Async HTTP-Servers does today. If you are using the right Future or CompletableFuture, Async HTTP-Servers are really good to increase throughput for IO intencive APIs.

As part of this article I also show how to use the Akka Actor Model and Akka HTTP. For next Blog articles I will show you how to secury HTTP API and use the Akka Cluster Feature.

So lets start code.The complete code for this article is available [here]()

### Setting up your project

```scala
def test()
```
