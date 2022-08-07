# Go guide collections

This is a collection of various go language guides, including those from the go team, corporations, personal blogs and talks.


- [Effective Go](https://go.dev/doc/effective_go)
- [CodeReviewComments](https://github.com/golang/go/wiki/CodeReviewComments)
- [Uber Go Style Guide](https://github.com/uber-go/guide/blob/master/style.md)
- [CommonMistakes](https://github.com/golang/go/wiki/CommonMistakes)
- [Go Proverbs](https://go-proverbs.github.io/)
- [Go安全指南](https://github.com/Tencent/secguide/blob/main/Go%E5%AE%89%E5%85%A8%E6%8C%87%E5%8D%97.md)
- [bahlo's Go Styleguide](https://github.com/bahlo/go-styleguide)

- [The Go Memory Model](https://go.dev/ref/mem)：可以着重看 **Incorrect synchronization** 这一小节中的错误示例，尽量避免在日常编程时犯错。
- [A Guide to the Go Garbage Collector](https://go.dev/doc/gc-guide)

- [go-profiler-notes](https://github.com/DataDog/go-profiler-notes)：主要内容在 [The Busy Developers's Guide to Go Profiling, Tracing and Observability](https://github.com/DataDog/go-profiler-notes/blob/main/guide/README.md) 中，包括了 CPU，Memory，Block，Mutex，Goroutine 等多种 profiler 的使用方式、适用场景和注意事项。

- [Scheduling In Go](https://www.ardanlabs.com/blog/2018/08/scheduling-in-go-part1.html)：分为 OS Scheduler，Go Scheduler 和 Concurrency 三个章节，循序渐进地阐述了 OS 线程调度，Goroutine 调度的基本原理，结合具体例子说明了对于不同性质的程序（CPU-Bound/IO-Bound） 使用并发/并行带来的效果。
