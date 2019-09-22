# Awesome Ruby Performance
A curated list of awesome Ruby Performance books, courses, trainings, conference talks, blogs and most inspiring open source contributors.

- [Awesome Ruby Performance](#awesome-ruby-performance)
	- [Books](#books)
	- [Video Courses](#video-courses)
	- [On-Site Trainings](#on-site-trainings)
	- [Upcoming conferences](#upcoming-conferences)
	- [Conference Talks](#conference-talks)
	- [Blogs](#blogs)
	- [Inspiring Open Source Contributors](#inspiring-open-source-contributors)
	- [Performance tools](#performance-tools)
	- [High Performance Libraries](#high-performance-libraries)
	- Article series
		- [Benchmarking](#benchmarking)
		- [Monitoring](#monitoring)
		- [Investigations](#investigations)
		- [JIT Optimizations](#jit-optimizations)
		- [Threading](#threading)
		- [Memory](#memory)
		- [RubyVM Internals](#rubyvm-internals)
  - [Intersting performance talks not about Ruby](#not-about-ruby)

## Books

* [Ruby Performance Optimization](https://pragprog.com/book/adrpo/ruby-performance-optimization) by Alexander Dymo


## Video Courses

* TODO


## On-Site Trainings

* TODO


## Upcoming conferences

* TODO

## Conference talks

Sorted from newest to oldest:
* 2019
    * TODO
* 2015
	* [On Memory](https://www.youtube.com/watch?v=yxhrYiqatdA) by John Crepezzi (2015.??.??, MountainWest RubyConf)
	(2017.03.17, DotNext)
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

### Application Insights
* New_Relic

## High Performance Libraries
* Booting code
  * [bootsnap](https://github.com/Shopify/bootsnap) - Boot large Ruby/Rails apps faster.
* C/Rust extensions
  * [fast_blank](https://github.com/SamSaffron/fast_blank) - Provides a C-optimized method for determining if a string is blank.
  * [yajl-ruby](https://github.com/brianmario/yajl-ruby) - A streaming JSON parsing and encoding library for Ruby (C bindings to yajl).
  * [oj] - Fast json library

## Article series

### Benchmarking
* [The Art of Benchmarking](http://mattwarren.org/2014/09/19/the-art-of-benchmarking/) by Matt Warren

### Monitoring
* TODO

### Investigations
* TODO

### JIT Optimizations
* TODO

### Threading
* TODO

### Memory
* TODO

### RubyVM Internals
* TODO

## Intersting performance talks not about Ruby
* [Emery Berger](https://www.youtube.com/watch?v=r-TLSBdHe1A)
* [Carl Cook](https://www.youtube.com/watch?v=NH1Tta7purM)
* [Brendan Gregg blog](http://www.brendangregg.com/)
