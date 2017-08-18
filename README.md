# Contents
  - [Summary](#summary)
  - [Online Resources](#online-resources)
    - [Architectural Patterns](#architectural-patterns)
    - [Database](#database)
    - [Logging](#logging)
    - [Object-Oriented Design](#object-oriented-design)
    - [Refactoring](#refactoring)
    - [Revision Control](#revision-control)
    - [Service-Oriented Architecture](#service-oriented-architecture)
    - [Others](#others)

## Summary

This is a curated list of the most didactic and/or deeply detailed must-read resources about software development.

## Online Resources

  ### Architectural Patterns

  _Is a general, reusable solution to a commonly occurring problem in software
  architecture within a given context. Architectural patterns are similar to software
  design pattern but have a broader scope._

  - Articles / Papers
    - [Command Query Responsibility Segregation (CQRS) by Martin Fowler](https://martinfowler.com/bliki/CQRS.html)
    - [Event Sourcing](https://docs.microsoft.com/en-us/azure/architecture/patterns/event-sourcing)
    - [Getting Started With DDD When Surrounded By Legacy Systems by Eric Evans](
    http://domainlanguage.com/wp-content/uploads/2016/04/GettingStartedWithDDDWhenSurroundedByLegacySystemsV1.pdf)
    - [Hexagonal Architecture by Alistair Cockburn](http://alistair.cockburn.us/Hexagonal+architecture)
    - [The Clean Architecture by Uncle Bob](
      https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html)
    - [The Onion Architecture by Jeffrey Palermo](http://jeffreypalermo.com/blog/the-onion-architecture-part-1/)

  - Books
    - [Domain-Driven Design: Tackling Complexity in the Heart of Software by Eric Evans](
    https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)

  - Videos
    - [Architecture the Lost Years by Uncle Bob](https://www.youtube.com/watch?v=WpkDN78P884) _(The Clean Architecture)_
    - [DDD & Microservices: At Last, Some Boundaries! by Eric Evans](https://www.youtube.com/watch?v=yPvef9R3k-M)
    - [What is programming MVC?](https://www.youtube.com/watch?v=1IsL6g2ixak)

  ### Database

  _A database is an organized collection of data. It is the collection of schemas, tables,
  queries, reports, views, and other objects._

  - Books
    - [SQL Indexing and Tuning by Markus Winand](http://use-the-index-luke.com/) (**_Free web-edition_**)

  ### Logging

  _In computing, a logfile is a file that records either events that occur in an operating system
  or other software runs, or messages between different users of a communication software.
  Logging is the act of keeping a log._

  - Articles / Papers
    - [Logging levels: the wrong abstraction, by Daniel Lebrero](https://labs.ig.com/logging-level-wrong-abstraction)
    - [Tracing Request IDs by Brandur](https://brandur.org/request-ids)
    - [The Log: What every software engineer should know about real-time data's unifying abstraction by Jay Kreps](
    https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)

  ### Object-Oriented Design

  _Object-Oriented Design is the process of planning a system of interacting
  objects for the purpose of solving a software problem._

  - Articles / Papers
    - [Dealing with Properties by Martin Fowler](https://martinfowler.com/apsupp/properties.pdf)
    - [Keep It DRY, Shy, and Tell the Other Guy by Andy Hunt and Dave Thomas](http://media.pragprog.com/articles/may_04_oo1.pdf)
    - [SRP: The Single Responsibility Principle](
    https://drive.google.com/file/d/0ByOwmqah_nuGNHEtcU5OekdDMkk/view)
    - [The Open-Closed Principle](
    https://drive.google.com/file/d/0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1/view)
    - [The Liskov Substitution Principle](
    https://drive.google.com/file/d/0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh/view)
    - [The Interface Segregation Principle](
    https://drive.google.com/file/d/0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi/view)
    - [The Dependency Inversion Principle](
    https://drive.google.com/file/d/0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz/view)

  - Videos
    - [Nothing is Something by Sandi Metz](https://www.youtube.com/watch?v=9lv2lBq6x4A)
    - [SOLID Object-Oriented Design by Sandi Metz](https://www.youtube.com/watch?v=v-2yFMzxqwU)

  ### Refactoring

  _Code refactoring is the process of restructuring existing computer code—changing the factoring—without
  changing its external behavior. Refactoring improves nonfunctional attributes of the software._

  - Articles / Papers
    - [On the Criteria To Be Used in Decomposing Systems into Modules by David Parnas](
    https://www.cs.umd.edu/class/spring2003/cmsc838p/Design/criteria.pdf) _(Decomposing)_

  - Videos
    - [Get a Whiff of This by Sandi Metz](https://www.youtube.com/watch?v=PJjHfa5yxlU) _(Code Smells)_

  ### Revision Control

  _Revision control is any kind of practice that tracks and provides control over changes to source code._

  - Articles / Papers
    - [Gitflow - A successful Git branching model by Vincent Driessen](http://nvie.com/posts/a-successful-git-branching-model/)
    - [GitLab Flow](https://docs.gitlab.com/ee/workflow/gitlab_flow.html)
    - [GitHub Flow by Scott Chacon](http://scottchacon.com/2011/08/31/github-flow.html)
    - [Git Style Guide by Agis Anastasopoulos](https://github.com/agis/git-style-guide)

  - Books
    - [Pro Git by Scott Chacon and Ben Straub](https://git-scm.com/book/en/v2)

  ### Service-Oriented Architecture

  _A service-oriented architecture (SOA) is a style of software design where services are provided
  to the other components by application components, through a communication protocol over a network.
  The basic principles of service-oriented architecture are independent of vendors, products and technologies._

  - Articles / Papers
    - [SEDA: An Architecture for Well-Conditioned, Scalable Internet Services by Matt Welsh, David Culler and Eric Brewer](
    http://www.sosp.org/2001/papers/welsh.pdf)
    - [Twelve-factor App Methodology by Adam Wiggins](https://12factor.net/)

  ### Others

  _Last but not least._

  - Articles / Papers
    - [Learn Regex by Zeeshan Ahmed](https://github.com/zeeshanu/learn-regex)
    - [Semantic Versioning Specification (SemVer) by Tom Preston-Werner](http://semver.org/)
    - [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!) by Joel Spolsky](
      https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)
    - [Time by Emil Mikulic](https://unix4lyfe.org/time/)
    - [The Infinite Hows (or, the Dangers Of The Five Whys) by John Allspaw](
    https://www.kitchensoap.com/2014/11/14/the-infinite-hows-or-the-dangers-of-the-five-whys/) _(Post-hoc/Postmortems)_
    - [What every web developer must know about URL encoding by Stéphane Épardaud](
    https://www.talisman.org/~erlkonig/misc/lunatech%5Ewhat-every-webdev-must-know-about-url-encoding/)
    - [What Every Programmer Should Know About Memory by Ulrich Drepper](https://www.akkadia.org/drepper/cpumemory.pdf)
    - [What Every Programmer Should Know About SEO](http://katemats.com/what-every-programmer-should-know-about-seo/)
    - [What's the Difference Between Continuous Integration, Continuous Deployment and Continuous Delivery? by Marko Anastasov](
    https://semaphoreci.com/blog/2017/07/27/what-is-the-difference-between-continuous-integration-continuous-deployment-and-continuous-delivery.html)
    - [What technical details should a programmer of a web application consider before making the site public?](
    https://softwareengineering.stackexchange.com/questions/46716/what-technical-details-should-a-programmer-of-a-web-application-consider-before)
