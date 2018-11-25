<!--- trailing spaces are important to force a line break, i.e. <br/> in the
      generated document -->

# Vikram Jakhar

 * Email: vikram.jakhr@gmail.com
 * Github: <http://github.com/vikramjakhr>
 * Twitter handle: [@vikramjakhr](http://twitter.com/vikramjakhr)
 * Phone number: +91 8527054221
 * Online resume: <http://vikramjakhr.github.com/Resume>

![My image](https://avatars1.githubusercontent.com/u/10959156?s=150&v=4)

## Objectives

Most of what you'll see in this resume was self taught, it started as
a hobby in school and later became a career. So learning new things is
an important objective in my life. I am a team player; an energetic
and smart team that I like to work with and learn from is also an
important objective.

## Education

### Polytechnic University, Brooklyn, NY
Department of Electrical and Computer Engineering
B.S. Degree in Computer Engineering
Fall 2006 - Fall 2009

### Higher Technological Institute, Egypt
Department of Electrical Engineering
Enrolled in B.S. Degree in Electrical Engineering
Fall 2002 - Spring 2005

## Skills

I have in the past used the following tools and technologies:

- **Go** (professional). I've been using Go since early 2013 and have
    submitted bug fixes to the repo previously (see below).
- **Java** (professional). I've been using Java for more than 5 years,
    although I prefer not to use it anymore for many reasons.
- **C/C++** (professional). I've been using C/C++ for the past 2
  years, mainly to write services and libraries that will run under
  Linux.
- **Ruby** (moderate). I'm not not really a Rubyist but I use Ruby for
    most of my scripting needs and love it as a language. I also
    contributed to a couple of JRuby gems and reported bugs with JRuby
    and submitted patches to the repo when appropriate.
- **Scala** (moderate). I used Scala for quite sometime, mainly to
    build web services using **Scalatra**.
- **Java Threads/PThreads** (moderate). Aware of the common pitfalls
  associated with using threads and have good debugging skills with
  threading issues.
- **Bash** (moderate). I'm by no means a good bash scripter but since
  the shell is the heart of all Unix systems, I'm forced to use it on
  a daily basis and get better at it everyday.
- **NoSQL**. I have recently used Redis for caching time series data
  that is frequently requested by client applications.  I also setup
  and maintained Cassandra as a time series db. I'm also the coauthor
  and maintainer of [InfluxDB](https://github.com/influxdb/influxdb) a
  timeseries database written entirely in Golang and using many NoSQL
  design concepts and tradeoff.
- **Linux Administration**. I'm not a sysadmin, but since I use Linux
  personally and develop services that runs on Linux, I became
  familiar with modifying kernel parameters such as choosing different
  I/O schedulers as well as tools to debug and understand performance
  issues (e.g. iotop, dstat, etc.).
- **SQL** (moderate). I know just enough SQL to get my job done and
    look up the documentation when it gets complicated.
- **Other languages**. I've previously used Clojure, Groovy/Grails,
    Rails, F#, Javascript, CoffeeScript, Haskell for small projects
    and for fun.

## Experience

### Professional experience

#### Errplane/InfluxDB

##### Software Engineer - July 2013 to November 2014

Errplane is a cloud-based platform for monitoring application
performance, exceptions, uptime, and custom metrics in
real-time. Errplane open-sourced the core data store, InfluxDB, a
lightweight distributed time series, events, and metrics database
written entirely in Golang.

As part of being at Errplane, I worked on the following projects:

- Co-author the initial design of InfluxDB.
- Build InfluxDB's query parser in yacc and lex for InfluxDB
- Coordinate the open source community that were built around
  InfluxDB. InfluxDB has gained the interest of the open source
  community and new tools and libraries are constantly built by the
  community. The tools range from command line interfaces to plugins
  for metric collection and visualization tools.
- Review patches and other changes requested by team members and the
  community.
- Write and maintain a local metric collection agent, that can monitor
  cpu, memory, load and processes possibly restarting them when a
  problem is detected.

#### Thomson Reuters

##### Software Engineer Contractor - December 2012 to July 2013

As part of a team of two contractors we were tasked with building a
drop-in replacement for
[Microsoft LCS](http://msdn.microsoft.com/en-us/library/aa167872%28v=office.11%29.aspx). The
responsibilities included the following:

- Implement a [SIP](http://www.ietf.org/rfc/rfc3261.txt) chat server
  that is backward compatible with LCS and supports all of
  [Microsoft's extensions](http://msdn.microsoft.com/en-us/library/cc246115.aspx)
  to SIP and written entirely in Golang.
- Integrate with other Thomson Reuters services and infrastructure.
- Federate with other networks, e.g. Yahoo! and MSN which used a
  slight variation of SIP.
- Communicate with a large team of developers, operations and QA teams
  located across the globe including Bangkok, London and New York
  City.
- Support hundreds of thousands of users logged in simultaneously to
  the system and scale horizontally.

#### Benchmark Solutions.

##### Software Engineer - February 2010 to December 2012

As an early employee at Benchmark Solutions I was responsible for
architecting, developing and maintaining a wide range of services and
processes that consitutes our realtime market data infrastructure
mostly built using open source software.

Working at Benchmark gave me the chance to get exposed to the Fixed
Income market and to build a complicated system by breaking it down
into smaller services/modules that are easy to build and
maintain. Below is an overview of the projects I worked on and
experiences I gained:

- **SINAPS**. Although it started as a web service to serve historical
  prices as well as last value data (most recent price) to our client
  applications. It soon became the internal tool to easily inspect
  data using a browser or pragmatically using the libraries that
  were built for Matlab, C, Java and Ruby. The service grew to
  encapsulate more complicated operations that were commonly used,
  such as filtering, averaging and joining multiple time
  series. SINAPS was written in Scala using Scalatra.
- **Cassandra/Hadoop**. Being a data company our time series db was an
  important piece of the architecture. We started with a proprietary
  solution and later moved to a Cassandra/Hadoop solution. I was responsible
  for architecting the schema, as well as building libraries for C/C++ (using
  the basic Thrift API), Ruby and Java to access the data with a simple API.
  Hadoop was used for batch jobs, such as end of day calculations.
- **Pubsub**. While at Benchmark I had the chance to use a wide range
  of messaging technologies and products, such as, 29West LBM (now
  known as Informatica Ultra messaging), 0mq and rabbit mq.
- **Team work**. My responsibilities required me to continuously
  communicate with the other teams, to make sure that they get what
  they needed to get their work done as well as collect requirements
  and discuss improvements to the infrastructure.

### Open source experience

Contributing back to the open source community is an important
activity in my daily life because I believe in the OSS mission and to
show gratitude to my fellow developers who continuously build awesome
software that I use on a daily basis.

- **[Golang](https://codereview.appspot.com/9795043)**. Fixed a bug in
  the tls certificate checking code that prevented certificates with
  long chains to be used in golang.
- **[InfluxDB](https://github.com/influxdb/influxdb)**. A
    lightweight distributed time series, events, and metrics database.
- **[Nokogiri](https://github.com/sparklemotion/nokogiri)**. Core
  maintainer of Nokogiri.
- **[JRuby](https://github.com/jruby/jruby)**. Found and fixed
  multiple bugs related to String encoding in JRuby 1.7 when running
  in 1.9 mode and timezone handling.
- **[Ruby](https://github.com/ruby/ruby)**. Submitted a new test to
  enhance coverage of String encoding as a result of a bug found in
  JRuby.
- **[Minix](http://www.minix3.org/)**. As a college project I ported
  the Linux O(1) scheduler which was designed and implemented by Ingo
  Molnár to the Minix Operating System, though this work wasn't
  published or contributed back to the Minix code base.

### Undergraduate experience

#### Database applications testing research

AGENDA is a software testing research project that focused on testing and verifying
database applications and their interactions with the database.

- **SWING**. Reimplemented AGENDA as a SWING application as opposed to
  a web app to provide a better user experience while reusing most of
  the components used by the web based implementation.
- **Input data generation**. Improved the implementation of the fake
  data generation phase by using an in memory db to filter the data
  sets that violated any of the schema constraints.
- **Papers**. Shahid, Chays, Frankl. Query-based Test Generation for
  Database Applications.  Proceedings of the 1st intentional workshop
  on testing database systems, June 2008.
