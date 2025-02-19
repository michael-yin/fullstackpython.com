title: Web App Performance
category: page
slug: web-app-performance
sortorder: 0606
toc: False
sidebartitle: Web App Performance
meta: Web application performance is affected by network latency, bandwidth, database queries, page size and many other factors.


Web application performance is affected by network latency, bandwidth, 
database queries, page size and many other factors.


### Load testing resources
* [Load Testing with Locust.io & Docker Swarm](https://wheniwork.engineering/load-testing-with-locust-io-docker-swarm-d78a2602997a)
  shows you how to set up load tests using [Docker](/docker.html) containers
  along with AWS for scaling up the tests.

* [HTTP Load Testing with Vegeta (and a dash of Python)](https://serialized.net/2017/06/load-testing-with-vegeta-and-python/)
  covers getting started with the [Vegeta](https://github.com/tsenart/vegeta)
  load tester and uses Python to analyze the tool's results.

* [Four reasons developers should write their own load tests](https://engineering.klarna.com/four-reasons-developers-should-write-their-own-load-tests-fac74c1be9f1)
  and 
  [four load testing mistakes developers love to make](https://engineering.klarna.com/four-load-testing-mistakes-developers-love-to-make-68b443f7e8a2)
  are opinionated pieces on how developer should use load testing to
  ensure their applications work properly under heavy usage.

* [Building a PostgreSQL load tester](https://blog.lawrencejones.dev/building-a-postgresql-load-tester/)
  explains how the [pgreplay-go](https://github.com/gocardless/pgreplay-go/)
  tool works and how to obtain performance metrics for a PostgreSQL database.


### Web app performance resources
* [A Primer in Web Performance](https://kiboit.com/performance) is a quick,
  straightforward one pager on why the topic matters and what causes bad
  website performance.

* [Web Performance 101](https://3perf.com/talks/web-perf-101/) introduces
  web application loading performance. There is a ton of great information
  on JavaScript, CSS and HTTP optimization as well as tools to use. 

* [Idle until urgent](https://philipwalton.com/articles/idle-until-urgent/)
  explains an issue the author found when measuring First Input Delay (FID) 
  on his site and what techniques he used to fix the problem.

* [How to Interpret Site Performance Tests](https://fly.io/articles/how-to-understand-performance-tests/)
  covers the difference between client, page and connection speed tests
  as well as a bit on caching performance.

* [Practical scaling techniques for websites](https://hackernoon.com/practical-scaling-techniques-for-web-sites-554a38dbd492)
  examines how to improve your website performance with asynchronous 
  [task queues](/task-queues.html), [database](/databases.html) optimization
  and [caching](/caching.html).

* The [Performance Testing Guidance for Web Applications](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/bb924375(v%3dpandp.10)
  book from Microsoft is a gem. There are chapters on foundations of 
  performance testing, modeling application usage and many other topics
  that are critical to working on web app performance.

* [awesome-scalability](https://github.com/binhnguyennus/awesome-scalability)
  provides a list with a crazy number of scaling and performance optimization 
  resources and tools by category.

* [The Infrastructure Behind Twitter: Scale](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2017/the-infrastructure-behind-twitter-scale.html)
  examines the evolution from having to buy your own hardware from vendors
  to run a service to the current days of being able to rely on cloud 
  providers for some or all workloads regardless of scale.
