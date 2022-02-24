# tutorial

## Papers:

[https://en.wikipedia.org/wiki/Log-structured_merge-tree](https://en.wikipedia.org/wiki/Log-structured_merge-tree):

In computer science, the log-structured merge-tree (also known as LSM tree, or LSMT[1]) is a data structure with performance characteristics that make it attractive for providing indexed access to files with high insert volume, such as transactional log data. LSM trees, like other search trees, maintain key-value pairs. LSM trees maintain data in two or more separate structures, each of which is optimized for its respective underlying storage medium; data is synchronized between the two structures efficiently, in batches.


[Separating Keys from Values in SSD-Conscious Storage](https://www.usenix.org/system/files/conference/fast16/fast16-papers-lu.pdf):

We present WiscKey, a persistent LSM-tree-based key-value store with a performance-oriented data layout that separates keys from values to minimize I/O amplification. The design of WiscKey is highly SSD optimized, leveraging both the sequential and random performance characteristics of the device. We demonstrate the advantages of WiscKey with both microbenchmarks and YCSB workloads. Microbenchmark results show that WiscKey is 2.5×–111× faster than LevelDB for loading a database and 1.6×–14× faster for random lookups. WiscKey is faster than both LevelDB and RocksDB in all six YCSB workloads.

## protocols:

* [Tus](https://tus.io/)

tus is a project aiming to make resumable file uploads easily usable and widely available. The most interesting parts of this project are the protocol specification and the many freely available client and server implementations.

## shell: 


[Bash Scripting Tutorial for Beginners](https://linuxconfig.org/bash-scripting-tutorial-for-beginners)

[Shell Scripting Tutorial](https://www.shellscript.sh/)

## golang: 

* :fire: :fire: :fire: :fire: [awesome-go](https://github.com/avelino/awesome-go)

* [Gin binding in Go: A tutorial with examples](https://blog.logrocket.com/gin-binding-in-go-a-tutorial-with-examples/#:~:text=What%20is%20Gin%20binding%3F,etc.%20to%20structs%20and%20maps.)


* [GraphQL Subscriptions With Go](https://betterprogramming.pub/graphql-subscriptions-with-go-6eb25dec5cd1)

In this article, I will walk you through how to implement GraphQL subscriptions with Go.

* [Go Vanity URLs](https://github.com/GoogleCloudPlatform/govanityurls) 

Go Vanity URLs is a simple Go server that allows you
to set custom import paths for your Go packages.
It also can run on Google App Engine.

* [LearnConcurrency](https://github.com/golang/go/wiki/LearnConcurrency)

This page links to resources for learning about concurrency in Go. 
The items are presented in order, from beginner material to advanced topics.

* [The Laws of Reflection](https://go.dev/blog/laws-of-reflection)

Reflection in computing is the ability of a program to examine its own structure, particularly through types; it’s a form of metaprogramming. It’s also a great source of confusion.


## spring java:

* [Spring Security with OAuth2, OpenID Connect [ Keycloak ]](https://www.youtube.com/watch?v=ts8uG_BOTuM)


## Frontends:

* [Micro Frontends Using Single-SPA and Module Federation](https://betterprogramming.pub/micro-frontends-using-single-spa-and-module-federation-81ec27d03aee)

In this article, I will walk you through how to implement a micro frontends app with single-spa and module federation in Webpack.



* [single-spa.js](https://single-spa.js.org/docs/getting-started-overview/)

> single-spa is a framework that enables you to easily set up a micro front-ends app.

single-spa is a framework for bringing together multiple JavaScript microfrontends in a frontend application. Architecting your frontend using single-spa enables many benefits, such as:

Use multiple frameworks on the same page without page refreshing (React, AngularJS, Angular, Ember, or whatever you're using)
Deploy your microfrontends independently
Write code using a new framework, without rewriting your existing app
Lazy load code for improved initial load time

* [Dependency cruiser](https://www.npmjs.com/package/dependency-cruiser)

Validate and visualise dependencies. With your rules. JavaScript. TypeScript. CoffeeScript. ES6, CommonJS, AMD.

## App Monitoring & Performance Tips:

[How to Measure Defect Escape Rate to Keep Bugs Out of Production](https://stackify.com/measure-defect-escape-rate/)

## Useful talks:

[Building Resilient Frontend Architecture • Monica Lent • GOTO 2019](https://www.youtube.com/watch?v=TqfbAXCCVwE)

[What is Apache Kafka®? (A Confluent Lightboard by Tim Berglund) + ksqlDB](https://www.youtube.com/watch?v=06iRM1Ghr1k)

:fire: :fire: :fire:[Lies, Damned Lies, and Metrics • Roy Osherove • GOTO 2019](https://www.youtube.com/watch?v=goihWvyqRow) :fire: :fire::fire:

