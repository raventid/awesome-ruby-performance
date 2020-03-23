# Awesome Ruby Performance
A curated list of awesome Ruby Performance books, courses, trainings, conference talks, blogs and most inspiring open source contributors. To get even more insights about performance you can take a look at [wiki pages](https://github.com/raventid/awesome-ruby-performance/wiki), they are work in progress now, but expect them to have more info.

- [Awesome Ruby Performance](#awesome-ruby-performance)
	- [Contributions](#contributions)
	- [Books](#books)
	- [Video Courses](#video-courses)
	- [On-Site Trainings](#on-site-trainings)
	- [Upcoming conferences](#upcoming-conferences)
	- [Conference Talks](#conference-talks)
	- [Blogs](#blogs)
	- [Inspiring Open Source Contributors](#inspiring-open-source-contributors)
	- [Performance tools](#performance-tools)
	- [High Performance Libraries](#high-performance-libraries)
	- [Benchmarks](#benchmarks)
	- Article series
		- [Benchmarking](#benchmarking)
		- [Monitoring](#monitoring)
		- [Investigations](#investigations)
		- [JIT Optimizations](#jit-optimizations)
		- [Threading](#threading)
		- [Memory](#memory)
		- [RubyVM Internals](#rubyvm-internals)
	- Official Ruby bugtracker notes
		- [CPU Improvements](#cpu-improvements)
		- [Memory Improvements](#memory-improvements)
	- [Interesting performance talks not about Ruby](#interesting-performance-talks-not-about-ruby)

## Contributions
  Have you ever seen an interesting talk about Ruby performance and it's not listed here? Send a pull request. Have you ever read an interesting article about Ruby performance and it's not listed here? Send a pull request. Did you write an article? Send a pull request. Know interesting blogger, who writes about Ruby performance? You know what to do!

  Do not forget to include language remark: 🇯🇵 🇰🇷 🇩🇪 🇨🇳 🇺🇸 🇫🇷 🇪🇸 🇮🇹 🇷🇺 🇬🇧

## Books

* [Ruby Performance Optimization](https://pragprog.com/book/adrpo/ruby-performance-optimization) by Alexander Dymo
* [Ruby Under a Microscope](http://patshaughnessy.net/ruby-under-a-microscope) by Pat Shaughnessy

## Video Courses

* TODO


## On-Site Trainings

* TODO


## Upcoming conferences

* TODO

## Conference talks

Sorted from newest to oldest:
* 2019
	* [Ruby CPU and Memory - Pareto principle](https://www.youtube.com/watch?v=eYhJWoxgoKA) by Юлиан Покровский (Oct 27, 2019, RubyRussia)
* 2015
	* [On Memory](https://www.youtube.com/watch?v=yxhrYiqatdA) by John Crepezzi (Mar 30, 2015, MountainWest RubyConf)
* Older
	* TODO

## Blogs

* [SpeedShop](https://www.speedshop.co/)

## Inspiring Open Source Contributors

* [Nate Berkopec](https://github.com/nateberkopec)

## Performance tools
* Benchmarking
  * [benchmark-ips](https://github.com/evanphx/benchmark-ips) - Provides iteration per second benchmarking for Ruby.
* Profiling
  * Rack
    * [Derailed Benchmarks](https://github.com/schneems/derailed_benchmarks) - A series of things you can use to benchmark a Rails or Ruby app.
    * [rack-mini-profiler](https://github.com/MiniProfiler/rack-mini-profiler) - Profiler for your development and production Ruby rack apps.
  * Pure Ruby
    * [batch-loader](https://github.com/exaspark/batch-loader) – A generic lazy batching mechanism to avoid N+1 DB queries, HTTP queries, etc.
    * [bullet](https://github.com/flyerhzm/bullet) - Help to kill N+1 queries and unused eager loading.
    * [Peek](https://github.com/peek/peek) - Visual status bar showing Rails performance.
    * [stackprof](https://github.com/tmm1/stackprof) - a sampling call-stack profiler for ruby 2.1+
    * [Rbkit](https://github.com/code-mancers/rbkit) - profiler for Ruby. With a GUI.
    * [rbspy](https://github.com/rbspy/rbspy) - Sampling profiler for any Ruby process.
    * [ruby-prof](https://github.com/ruby-prof/ruby-prof) - A code profiler for MRI rubies.
    * [speedscope](https://github.com/jlfwong/speedscope) - A fast, interactive web-based viewer for performance profiles. An alternative viewer for FlameGraphs. Will happily display multi-megabyte profiles without crashing your browser.
* Linters, recommendation tools (possibly runnable on CI)
  * [fasterer](https://github.com/DamirSvrtan/fasterer) - Don't make your Rubies go fast. Make them go fasterer
### Application Insights
* New_Relic

## High Performance Libraries
* Booting code
  * [bootsnap](https://github.com/Shopify/bootsnap) - Boot large Ruby/Rails apps faster.
* C/Rust extensions
  * [fast_blank](https://github.com/SamSaffron/fast_blank) - Provides a C-optimized method for determining if a string is blank.
  * [yajl-ruby](https://github.com/brianmario/yajl-ruby) - A streaming JSON parsing and encoding library for Ruby (C bindings to yajl).
  * [oj](https://github.com/ohler55/oj) - A fast JSON parser and Object marshaller as a Ruby gem.
* Memory
  * [nakayoshi_fork](https://github.com/ko1/nakayoshi_fork) - solves CoW friendly problem on MRI 2.2 and later
  
## Benchmarks
* Ruby in Web
  * [Concurrent HTTP requests in Ruby](https://github.com/exAspArk/concurrent_http_requests)
  * [Benchmark some Ruby web microframeworks, just for fun](https://github.com/luislavena/bench-micro)
## Article series

### Benchmarking
* [The Art of Benchmarking](http://mattwarren.org/2014/09/19/the-art-of-benchmarking/) by Matt Warren

### Monitoring
* TODO

### Investigations
* [Как я провёл две недели в поисках утечки памяти](http://be9.ru/2015/09/12/memory-leak.html) by Олег Дашевский. "Это история о поисках утечки памяти. Она довольно длинная, потому что я привожу массу подробностей. Почему я решил описать свои приключения? Дело не только в практическом стремлении сохранить все мелкие скрипты и куски кода. Мне на минуточку показалось, что это и есть UNIX way – то, что меня вело. Каждый шаг был связан с очередной небольшой утилитой или библиотекой, которая хорошо решает свою задачу. И я в итоге достиг успеха."
* [How I spent two weeks hunting a memory leak in Ruby](http://www.be9.io/2015/09/21/memory-leak/) by Oleg Dashevskii. "This is a story about hunting a memory leak. A long story, because I go into much detail. Why describe my adventures? Not that I wanted to save all those tiny code pieces and scripts only. It rather occurred to me that it was UNIX way which I had pursued. Every step was related to yet another small utility, or a library, which solves its task well. And finally I succeeded."

### JIT Optimizations
* TODO

### Threading
* TODO

### Memory
* [Debugging hidden memory leaks in Ruby](https://samsaffron.com/archive/2019/10/08/debugging-unmanaged-and-hidden-memory-leaks-in-ruby) - "This article covers tools and tricks you can use to attack leaks that you can not easily introspect in Ruby. In particular I will discuss mwrap, heaptrack, iseq_collector and chap." by Sam Saffron (2019-10-15)
* [What causes Ruby memory to bloat](https://www.joyfulbikeshedding.com/blog/2019-03-14-what-causes-ruby-memory-bloat.html) - How memory allocation works in Ruby and how to improve it with malloc_trim API.
* [The Definitive Guide to Ruby Heap Dumps, Part I](https://blog.codeship.com/the-definitive-guide-to-ruby-heap-dumps-part-i/) - “When you can’t reproduce memory bloat, here’s how to work with a heap dump.” by Richard Schneeman (Last updated: 2017-06-19)
* [The Definitive Guide to Ruby Heap Dumps, Part II](https://blog.codeship.com/the-definitive-guide-to-ruby-heap-dumps-part-ii/)- “When you can’t reproduce memory bloat, here’s how to work with a heap dump.” by Richard Schneeman (Last updated: 2017-06-19)

### RubyVM Internals
* TODO

## Official Ruby bugtracker notes

### CPU Improvements
* TODO

### Memory Improvements
* 2019
  * [Introduce malloc_trim(0) in full gc cycles](https://bugs.ruby-lang.org/issues/15667) - Per Hongli's excellent article it looks like malloc_trim can help tremendously with memory bloat issues.
* 2018
  * [set M_ARENA_MAX for glibc malloc](https://bugs.ruby-lang.org/issues/14759) - Not everybody benefits from jemalloc and the extra download+install time is not always worth it. Lets make the user experience for glibc malloc users better, too.
  * [Use jemalloc by default?](https://bugs.ruby-lang.org/issues/14718)

## Interesting performance talks not about Ruby
* [Emery Berger](https://www.youtube.com/watch?v=r-TLSBdHe1A)
* [Carl Cook](https://www.youtube.com/watch?v=NH1Tta7purM)
* [Brendan Gregg blog](http://www.brendangregg.com/)
