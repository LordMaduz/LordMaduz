# Ruchira Rajapaksha

**AI Product Engineer at Arbitr (formerly Straker), in Auckland, New Zealand.**

I started out wanting to build video games as a kid. Ended up building something far more interesting instead. Now I'm at Arbitr, an AI translation platform, working on the checks that hand work to a person when the AI isn't sure.

[Portfolio](https://lordmaduz.github.io/ruchira.codes/) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/ruchirarajapaksha/) &nbsp;·&nbsp; [Book a 20-minute chat](https://cal.com/ruchira-rajapaksha) &nbsp;·&nbsp; [Hugging Face](https://huggingface.co/maduzrajapaksha)

## What I'm working on

Arbitr is an AI-first translation platform. Clients upload their content, AI agents and machine translation do the first pass, and people review what needs a human. The agents sort content, pick and chase vendors, post-edit, check style and visual layout, and score quality.

I work across the platform's services and its three web apps, mostly on the orchestration side that sends work to the agents and acts on what comes back. That means deciding when a job can run on its own and when it goes to a person, adding guardrails on agent output, and getting stuck jobs moving again. Most of it is Python, with FastAPI, PydanticAI and Redis Streams.

That code is private. My [portfolio](https://lordmaduz.github.io/ruchira.codes/#work) walks through how the pieces fit.

## Things I've built

**[LandedNZ](https://github.com/LordMaduz/landednz-be)**, on my own, 2026<br>
A planner for moving to New Zealand. A rules engine builds your plan from your visa, city and family, and an AI chat answers questions about it.<br>
<sub>Next.js, Fastify, PostgreSQL with pgvector, Claude API</sub>

**Global minimum tax engine**, DBS Bank, 2024 to 2025<br>
New OECD rules set a 15% minimum tax with a different formula in every country. Tax teams edit the rules themselves, so a formula change doesn't wait for a release.<br>
<sub>Java, Spring Boot, MVEL, MongoDB</sub>

**Trade file processing**, DBS Bank, 2022 to 2024<br>
Bloomberg sends the derivatives desk files all day, some over 100 MB. I moved them to a reactive pipeline that streams them in parallel and keeps memory flat.<br>
<sub>Spring WebFlux, Project Reactor, AWS S3</sub>

**Food orders at lunch rush**, GrubTech, 2022<br>
Orders confirm straight away and reach the database shortly after, and stock stays in sync across brands.<br>
<sub>Redis, Redisson, Kafka, MongoDB</sub>

## Open source

Runnable examples that go with my articles:

- [Observability in Spring Boot 3 with OpenTelemetry](https://github.com/LordMaduz/Observability-In-Spring-Boot-3-With-OpenTelemetry)
- [Realtime event processing with reactive gRPC](https://github.com/LordMaduz/Realtime-Event-Processing-With-Reactive-gRPC)
- [Reactive GraphQL with Spring](https://github.com/LordMaduz/Reactive-Programming-with-GraphQL-and-Spring)
- [Dynamic config with Spring Cloud Config Server](https://github.com/LordMaduz/Dynamic-Config-Management-With-Spring-Cloud-Config-Server)

## Writing

I write on [Medium](https://medium.com/@maduz.ruchira) about the systems I work on, and I've written tutorials for [Baeldung](https://www.baeldung.com/author/ruchiramadhushanrajapaksha). Latest posts:

<!-- BLOG-POST-LIST:START -->
- [Are You Giving Away Your Writing’s Worth with Friend Links?](https://medium.com/illumination/are-you-giving-away-your-writings-worth-with-friend-links-54f62aea8d11)
- [Is Partitioning for Targeted Data Access Still the Master Plan of Database Design?](https://levelup.gitconnected.com/is-partitioning-for-targeted-data-access-still-the-master-plan-of-database-design-1684d7bbb0a7)
- [Is Modern Concurrency Aligned with Joe Armstrong’s Actor Model and Simplicity Principles?](https://levelup.gitconnected.com/is-modern-concurrency-aligned-with-joe-armstrongs-actor-model-and-simplicity-principles-a6c67d47c092)
- [I Studied Reactor Kafka So You Don’t Have To: Handling BackPressure (Part 1)](https://levelup.gitconnected.com/i-studied-reactor-kafka-so-you-dont-have-to-here-s-what-i-learned-handling-backpressure-part-1-f7ffca82295a)
- [Is Rust a Pure Functional Programming Language Or Just Pretending To Be One?](https://levelup.gitconnected.com/is-rust-a-functional-programming-language-or-just-pretending-to-be-one-d03cf8db38c9)
<!-- BLOG-POST-LIST:END -->

## Tools

These days it's mostly Python (FastAPI, PydanticAI, LiteLLM) with Vue and Nuxt on the front end. Before Arbitr I spent years on Java and Spring, with Kafka, Redis and MongoDB, running on AWS and Kubernetes.

<sub>Off the clock I'm usually on the PlayStation.</sub>
