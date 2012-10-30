<!--- trailing spaces are important to force a line break, i.e. <br/> in the
      generated document -->

# John V. Shahid

 * Email/GTalk: <jvshahid@gmail.com>
 * Github: <http://github.com/jvshahid>
 * Twitter handle: [@jvshahid](http://twitter.com/jvshahid)
 * Phone number: 718-730-0780
 * Online resume: <http://jvshahid.github.com/Resume>

![My image](http://www.gravatar.com/avatar/2736d9750eb13425e9bf70f112753c49?s=150)

## Objectives (What am I looking for ?)

I love working on cool stuff with a bunch of smart people.  Most of
what you'll see in this resume was self taught, it started as a hobby
in high school and later became my career. So learning new things is an
important objective in my life as well.

## Education

### Polytechnic University, Brooklyn, NY  
Department of Electrical and Computer Engineering  
B.S. Degree in Computer Engineering  
Fall 2006 - Fall 2009

### Higher Technological Institute, Egypt  
Department of Electrical Engineering  
Enrolled in B.S. Degree in Electrical Engineering  
Fall 2002 - Spring 2005

## Skills (What do I know ?)

I have been programming professionally since 2010, mainly using
the following technologies:

- **Ruby** (moderate). I'm not not really a Rubyist but I use Ruby for most of my scripting needs and love it as a language.
- **Scala** (moderate). I've been using Scala for quite sometime now, mainly to build web services using **Scalatra**.
- **Java** (professional). I've been using Java for more than 5 years, although I prefer not to use it anymore for many reasons.
- **C/C++** (professional). I've been using C/C++ for the past 2 years, mainly to write services and libraries that will run
  under Linux.
- **Bash** (moderate). I'm by no means a good bash scripter but since the shell is the heart of all Unix systems,
  I'm forced to use it on a daily basis and get better at it everyday.
- **Java Threads/PThreads** (moderate). Aware of the common pitfalls associated with using threads and have good debugging skills
  with threading issues.
- **NoSql**. I have recently used Redis for caching time series data that is frequently requested by client applications.
  I also setup and maintained Cassandra as a time series db.
- **Linux Administration**. I don't call myself a sysadmin, but since I use Linux personally and develop services
  that runs on Linux, I became familiar with modifying kernel parameters such as choosing different I/O schedulers
  as well as tools to debug and understand performance issues (e.g. iotop, dstat, etc.).
- **SQL** (moderate). I know just enough SQL to get my job done and look up the documentation when it gets complicated.
- **Other languages**. I've previously used Clojure, Groovy/Grails, Rails, F#, Javascript, Haskell for small projects and for fun.

## Experience (What have I done ?)

### Professional experience

#### Benchmark Solutions.

##### Software Engineer - February 2010 to Present

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

Contributing back to the open source community is an important activity
in my daily life because I believe in the OSS mission and to show gratitude
to my fellow developers who continuously build awesome software that I use
on a daily basis.

- **[Nokogiri](https://github.com/sparklemotion/nokogiri)**. Core
  maintainer of Nokogiri.
- **[JRuby](https://github.com/jruby/jruby)**. Found and fixed a bug
  related to String encoding in JRuby 1.7 when running in 1.9 mode.
- **[Ruby](https://github.com/ruby/ruby)**. Submitted a new test to
  enhance coverage of String encoding as a result of a bug found in
  JRuby.
- **[Minix](http://www.minix3.org/)**. While in college I ported the
  Linux O(1) scheduler which was designed and implemented by Ingo
  Malner to the Minix Operating System, though this work wasn't
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
