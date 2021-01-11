:orphan:

================================
Marsel Mavletkulov: Go developer
================================

I find professional satisfaction in building reliable services, reasoning about their boundaries,
writing documentation and clear code.
It is important for me to solve meaningful problems with high impact.

- https://github.com/marselester
- https://marselester.com
- https://angel.co/u/marselester
- https://twitter.com/marselester

I prefer Go, Django, PostgreSQL, Kafka, Kubernetes.

Work Experience
---------------

**Software Architect** at fintech startup Coins.ph_ 🚀
August 2017 — September 2020
**Senior Software Engineer**
July 2014 — August 2017

- built a wallet service (Django, PostgreSQL) which helped the company to grow from thousands to over **10 millions** of customers;
- designed a new ledger (Go, PostgreSQL, Kafka) to solve scalability issues and led the team focused on its delivery;
- ran an architecture guild meetings, gave talks about architecture,
  `Kafka <https://go-talks.appspot.com/github.com/marselester/kafka-for-gophers/kafka.slide>`_,
  `LSM storages <https://go-talks.appspot.com/github.com/marselester/storage-engines/log-structured-engine.slide>`_,
  `PostgreSQL <https://go-talks.appspot.com/github.com/marselester/storage-engines/postgres-lingo.slide>`_,
  `scalability of web services <https://go-talks.appspot.com/github.com/marselester/scalability/scalability.slide>`_,
  `SaltStack <https://slides.com/marselester/saltstack>`_;
- set up CI, and infrastructure based on SaltStack which
  helped to quickly provision dozens of EC2 instances to cope with exponential growth;
- introduced ELK, Prometheus, Jaeger to help developers with troubleshooting;
- decoupled and redesigned the core services from Flask monolith to scale them independently, e.g.,
  currency quotes service, account management service (sign up/in, TFA);
- helped with Go adoption (no web or `testing frameworks`_, no ORMs):
  common `project structure <https://marselester.com/how-to-structure-go-projects.html>`_
  leveraging Go kit components (JSON/gRPC transports, telemetry, rate limiter, circuit breaker);
- improved code quality, architecture and advocated for both (conventions/proposals gardening similar to Go proposals);
- as a first remote developer helped to scale the engineering team which ended up working remotely;
- fostered an engineering culture of service ownership;
- been on-call to provide a quick incident response;

**Python Developer** contractor at icon fonts generator Fontastic_ (Webalys_) 🙂
January 2014 — July 2014

- improved project monetization with SVG sprite hosting and billing, e.g., implemented
  recurring PayPal payments, usage limits of font hosting,
  coroutine based AWS S3 and CloudFront log analyzer);
- introduced infrastructure as code (Ansible) to limit human errors;
- refactored and documented backend (Django, PostgreSQL) reducing tech debt;

**Python Developer** at cloud-based file upload SaaS Uploadcare_ 🆙
November 2012 — August 2013

- integrated Stripe so that the company could start generating revenue;
- developed customer dashboards (Django, PostgreSQL);
- improved API client pyuploadcare_ (mass refactoring, documentation_, Python3 support, first major release);

**Python Developer** at concert organization startup FanGid.com_ 🤟
July 2012 — October 2012

- launched the project in 3 months (two developers) and it started to sell tickets;
- developed the following Django components:
  social auth, voting system, concert's pages, singer's profile page,
  displaying similar bands, email sending, monetization (tickets, orders, discounts, payments);

🎓
--

In 2005 I enrolled in Samara State Aerospace University,
then in 2007 relocated and continued the curriculum at
Ufa State Aviation Technical University, graduating in 2012 with
Master's degree in Computer Science.

.. _Coins.ph: https://coins.ph
.. _testing frameworks: https://golang.org/doc/faq#testing_framework
.. _Fontastic: http://fontastic.me
.. _Webalys: http://www.webalys.com
.. _Uploadcare: https://uploadcare.com
.. _pyuploadcare: https://github.com/uploadcare/pyuploadcare
.. _documentation: https://pyuploadcare.readthedocs.org
.. _FanGid.com: http://fangid.com

.. image:: _static/talk.jpg
   :alt: Marsel Mavletkulov: Go developer
