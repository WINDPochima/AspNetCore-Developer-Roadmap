# نقشه راه برنامه نویسی با Asp.net core

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Backers on Open Collective](https://opencollective.com/AspNetCore-Developer-Roadmap/backers/badge.svg)](#backers)
[![Sponsors on Open Collective](https://opencollective.com/AspNetCore-Developer-Roadmap/sponsors/badge.svg)](#sponsors)

- [مشاهده فایل Read-me به زبان چینی سنتی](ReadMe.zh-Hant.md)
- [مشاهده فایل Read-me به زبان چینی ساده سازی شده](ReadMe.zh-Hans.md)
- [مشاهده فایل Read-me به زبان ژاپنی](ReadMe.ja.md)
- [مشاهده فایل Read-me به زبان ترکی](ReadMe-tr.md)

> نقشه راه تبدیل شدن به یک برنامه نویس [ASP.NET Core](https://docs.microsoft.com/aspnet/core) در سال 2023:

در پایین این متن میتوانید یک چارت که نمایشگر راه هایی که میتوانید انتخاب کند و کتابخانه های که میتوانید برای تبدیل شدن به یک برنامه نویسی ASP.NET core بیاموزید. من این چارت را به عنوان یک راهنما برای هر کسی که از من راجب اینکه دیگر باید چه چیزی را به عنوان یک برنامه نویس ASP.NET core بیاموزم ساختم.

## سلب مسئولیت

> چرایی ساخت این نقشه راه این بود که به شما در درک فضای کار این تکنولوژی کمک کند. این نقشه به شما کمک میکند که در پاسخ به اینکه چه چیزی دیگری را باید بیاموزید گمراه نشوید, نه اینکه تلاش کند صرفا فناوری های پرطرفدار روز را به شما معرفی کند. شما باید به این درک برسید که چرا یک ابزار میتواند برای یک کار مناسب باشد و برای کار دیگر نه. ابزار های ترند شده لزوما برای تمامی استفاده ها مناسب نیستند.


## ستاره بدهید! :star:

اگر این پروژه را دوست دارید و از آن برای یادگیری یا شروع کار استفاده کرده اید میتوانید یک ستاره به ما بدهید. ممنون!

## نقشه راه

![نشقه راه](./aspnetcore-developer-roadmap.png)

## منابع

1. توانایی های عمومی و پایه برنامه نویسی
   - [Git](https://git-scm.com/doc) را یاد بگیرید, چند مخزن یا همان ریپازتوری در گیتاهاب بسازید [GitHub](https://docs.github.com/en/get-started/quickstart), کد های خودتان را با دیگران به اشتراک بگذارید
   - [HTTP(S) protocol](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview) را درک کنید, روش های ارسال درخواست یا همان Request methods ([GET](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET), [POST](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/POST), [PUT](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/PUT), [PATCH](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/PATCH), [DELETE](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/DELETE), [OPTIONS](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/OPTIONS), etc.)
   - [TLS](https://www.cloudflare.com/learning/ssl/transport-layer-security-tls/) چیست?
   - [SSL](https://www.cloudflare.com/learning/ssl/what-is-ssl/) چیست?
   - از جستجو در گوگل نترسید, [Power Searching with Google](http://www.powersearchingwithgoogle.com)
   - شروع به استفاده از [ChatGPT](https://chat.openai.com/chat) کنید
   - [چند کتاب در باره الگوریتم ها و ساختمان داده ها بخوانید](https://www.interviewbit.com/blog/data-structures-and-algorithms-books)

2. C#
   - [C#](https://www.pluralsight.com/paths/c-10)
   - [.NET 7](https://devblogs.microsoft.com/dotnet/announcing-dotnet-7)
   - یادگیری [dotnet CLI](https://docs.microsoft.com/dotnet/core/tools)

3. مبانی SQL
   - [Pluralsight Learning Path: Querying Data with T-SQL from SQL Server](https://www.pluralsight.com/paths/querying-data-with-t-sql-from-sql-server)

4. پایه های ASP.NET Core
   - [MVC](https://docs.microsoft.com/en-us/aspnet/core/mvc/overview)
   - [REST](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api)
   - [تنظیمات و پیکربندی برنامه](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration)
   - [Middlewares یا میان افزار ها](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware)
   - [Filters & Attributes فیلتر ها و ویژگی ها](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/filters)
   - [Authentication احراز هویت](https://docs.microsoft.com/en-us/aspnet/core/security/authentication)
   - [Authorization مجوز ها](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/introduction)
   - [IdentityServer](https://identityserver4.readthedocs.io/en/latest)
   - [OpenIddict](https://github.com/openiddict/openiddict-core)
   - [Auth0](https://auth0.com/docs)
   - [OIDC](https://openid.net/connect)
   - [Razor Pages](https://docs.microsoft.com/en-us/aspnet/core/razor-pages)
   - [Razor Components](https://docs.microsoft.com/en-us/aspnet/core/blazor/components)
   - دوره ها
      - [Pluralsight Learning Path: ASP.NET Core 6](https://www.pluralsight.com/paths/aspnet-core-6)
      - [Pluralsight Learning Path: ASP.NET Core 6 Web API](https://www.pluralsight.com/paths/aspnet-core-6-web-api)

5. SOLID
    - [اصل مسئولیت واحد /Single Responsibility Principle (SRP)](https://www.dotnetcurry.com/software-gardening/1148/solid-single-responsibility-principle)
    - [اصل باز-بسته/Open-Closed Principle (OCP)](https://www.dotnetcurry.com/software-gardening/1176/solid-open-closed-principle)
    - [اصل جایگزینی لیسکوف/Liskov Substitution Principle (LSP)](https://www.dotnetcurry.com/software-gardening/1235/liskov-substitution-principle-lsp-solid-patterns)
    - [اصل جداسازی رابط/Interface Segregation Principle (ISP)](https://www.dotnetcurry.com/software-gardening/1257/interface-segregation-principle-isp-solid-principle)
    - [اصل وارونگی وابستگی/Dependency Inversion Principle (DIP)](https://www.dotnetcurry.com/software-gardening/1284/dependency-injection-solid-principles)

6. ORM
    - [Entity Framework Core](https://learn.microsoft.com/en-us/ef/core)
       - Tutorials
          - [Pluralsight Learning Path: EF Core 6](https://www.pluralsight.com/paths/ef-core-6)
    - [Dapper](https://github.com/StackExchange/Dapper)
    - [RepoDB](https://github.com/mikependon/RepoDB)

7. Dependency Injection
    1. DI Containers
       - [Microsoft.Extensions.DependencyInjection](https://docs.microsoft.com/aspnet/core/fundamentals/dependency-injection)
       - [AutoFac](https://autofaccn.readthedocs.io/en/latest/integration/aspnetcore.html)
       - [Ninject](http://www.ninject.org)
       - [Castle Windsor](https://github.com/castleproject/Windsor)
	   - [Simple Injector](https://github.com/simpleinjector/SimpleInjector)
    2. [Life Cycles](https://docs.microsoft.com/aspnet/core/fundamentals/dependency-injection#service-lifetimes)
    3. [Scrutor](https://github.com/khellang/Scrutor)

8. Databases
    1. Relational
       - [SQL Server](https://www.microsoft.com/sql-server/sql-server-2019)
       - [PostgreSQL](https://www.postgresql.org)
       - [MariaDB](https://mariadb.org)
       - [MySQL](https://www.mysql.com)
    2. Search Engines
       - [ElasticSearch](https://www.elastic.co)
       - [Solr](http://lucene.apache.org/solr)
       - [Sphinx](http://sphinxsearch.com)
    3. NoSQL
        - On-Premises
          - [Redis](https://redis.io)
          - [MongoDB](https://docs.microsoft.com/aspnet/core/tutorials/first-mongo-app)
          - [Apache Cassandra](http://cassandra.apache.org)
          - [LiteDB](https://github.com/mbdavid/LiteDB)
          - [RavenDB](https://github.com/ravendb/ravendb)
          - [CouchDB](http://couchdb.apache.org)
       - Cloud
          - [CosmosDB](https://docs.microsoft.com/azure/cosmos-db)
          - [DynamoDB](https://aws.amazon.com/dynamodb)

9. Caching
    - [Memory Cache](https://docs.microsoft.com/aspnet/core/performance/caching/memory)
    - [Distributed Cache](https://docs.microsoft.com/aspnet/core/performance/caching/distributed)
       1. [Redis](https://redis.io/)
          1. [StackExchange.Redis](https://stackexchange.github.io/StackExchange.Redis)
          2. [EasyCaching](https://github.com/dotnetcore/EasyCaching)
       2. [Memcached](https://memcached.org)
    - Application-Level
       - [Response Caching](https://learn.microsoft.com/en-us/aspnet/core/performance/caching/response)
       - [Output Caching](https://learn.microsoft.com/en-us/aspnet/core/performance/caching/output?source=recommendations)
       - [Entity Framework 2nd Level Cache](https://github.com/VahidN/EFCoreSecondLevelCacheInterceptor)

10. Log Frameworks
    - [Serilog](https://github.com/serilog/serilog)
    - [NLog](https://github.com/NLog/NLog)
      
11. API Clients & Communications
    1. REST
       - [Sieve](https://github.com/Biarity/Sieve)
       - [OData](https://learn.microsoft.com/en-us/odata/webapi/first-odata-api) 
       - [REPR Pattern](https://ardalis.com/mvc-controllers-are-dinosaurs-embrace-api-endpoints/)
            - [Minimal APIs](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/minimal-apis/overview)
            - [Fast Endpoints](https://github.com/FastEndpoints/FastEndpoints)
            - [Ardalis.Endpoints](https://github.com/ardalis/ApiEndpoints)
    2. [gRPC](https://docs.microsoft.com/en-us/aspnet/core/grpc)
    3. GraphQL
        - [HotChocolate](https://github.com/ChilliCream/hotchocolate)
        - [GraphQL-dotnet](https://github.com/graphql-dotnet/graphql-dotnet)

12. Real-Time Communication
    - [SignalR](https://docs.microsoft.com/aspnet/core/signalr)
    - [WebSockets](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/websockets)
   
13. Object Mapping
    - [AutoMapper](https://github.com/AutoMapper/AutoMapper)
    - [Mapster](https://github.com/MapsterMapper/Mapster)
    - [ExpressMapper](http://expressmapper.org/)
    - [AgileMapper](https://github.com/agileobjects/AgileMapper)
   
14. Background Task Scheduler
    - [Native BackgroundService](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services)
    - [HangFire](https://github.com/HangfireIO/Hangfire)
    - [Quartz](https://github.com/quartznet/quartznet)
    - [Coravel](https://github.com/jamesmh/coravel)    
    
15. Testing
    1. Unit Testing
       - Frameworks
          - [xUnit](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-dotnet-test)
          - [NUnit](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-nunit)
          - [MSTest](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-mstest)
       - Mocking
          - [Moq](https://github.com/moq/moq4)
          - [NSubstitute](https://github.com/nsubstitute/NSubstitute)
          - [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy)
       - Assertion
          - [FluentAssertion](https://github.com/fluentassertions/fluentassertions)
          - [Shouldly](https://github.com/shouldly/shouldly)
       - Fake Data Generators
          - [Bogus](https://github.com/bchavez/Bogus)
          - [AutoFixture](https://github.com/AutoFixture/AutoFixture)
          - [GenFu](https://github.com/MisterJames/GenFu)
    2. Integration Testing
       - [WebApplicationFactory](https://docs.microsoft.com/aspnet/core/test/integration-tests)
       - [TestServer](https://koukia.ca/integration-testing-in-asp-net-core-2-0-51d14ede3968)
    3. Snapshot Testing
       - [Verify](https://github.com/VerifyTests/Verify)
    4. Behavior Testing
       - [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore)
       - [BDDfy](https://github.com/TestStack/TestStack.BDDfy)
       - [LightBDD](https://github.com/LightBDD/LightBDD)
    5. E2E Testing
       - [Selenium](https://www.hanselman.com/blog/real-browser-integration-testing-with-selenium-standalone-chrome-and-aspnet-core-21)
       - [Puppeteer-Sharp](https://github.com/kblok/puppeteer-sharp)
    6. Performance Testing
       - [K6](https://github.com/grafana/k6)
       - [JMeter](https://github.com/apache/jmeter)
       - [Crank](https://github.com/dotnet/crank)
       - [Bombardier](https://github.com/codesenberg/bombardier)

16. Microservices
    1. Message-Brokers
       - [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-dotnet.html)
       - [Apache Kafka](https://github.com/confluentinc/confluent-kafka-dotnet)
       - [ActiveMQ](https://github.com/apache/activemq)
       - [Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview)
       - [NetMQ](https://github.com/zeromq/netmq)
    2. Message-Bus
       - [MassTransit](https://github.com/MassTransit/MassTransit)
       - [NServiceBus](https://github.com/Particular/NServiceBus)
       - [EasyNetQ](https://github.com/EasyNetQ/EasyNetQ)
       - [CAP](https://github.com/dotnetcore/CAP)
    3. API Gateway
       - [Ocelot](https://github.com/ThreeMammals/Ocelot)
       - [YARP](https://github.com/microsoft/reverse-proxy)
    4. Containerization
       - [Docker](https://www.docker.com)
    5. Orcherstration
       - [Kubernetes](https://kubernetes.io)
         - [Rancher](https://github.com/rancher/rancher)
         - [Kubectl](https://kubernetes.io/docs/reference/kubectl)
         - [K9s](https://github.com/derailed/k9s)
       - [Docker Swarm](https://docs.docker.com/engine/swarm)
    6. Other
       - [Orleans](https://github.com/dotnet/orleans)
       - [Proto.Actor](https://github.com/asynkron/protoactor-dotnet)
       - [Steeltoe](https://steeltoe.io)
       - [Dapr](https://github.com/dapr/dapr)
       - [Tye](https://github.com/dotnet/tye)

17. Continuous Integration & Continuous Delivery
    - [GitHub Actions](https://github.com/features/actions)
    - [Gitlab CI](https://docs.gitlab.com/ee/ci)
    - [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines)
    - [Travis CI](https://travis-ci.org)
    - [Jenkins](https://www.jenkins.io)
    - [Circle CI](https://circleci.com)
    - [TeamCity](https://www.jetbrains.com/teamcity)

18. Design Patterns
    - Categories
      - [Creational](https://docs.microsoft.com/azure/architecture/patterns/cqrs)
      - [Structural](https://www.dofactory.com/net/decorator-design-pattern)
      - [Behavioral](https://www.dofactory.com/net/strategy-design-pattern)
    - Tutorials
      - [Pluralsight Learning Path: Design Patterns in C#](https://www.pluralsight.com/paths/design-patterns-in-c)

19. Monitoring/Logging/Tracing/Alerting
    - Monitoring
       - On-Premises
          - [Prometheus](https://github.com/prometheus/prometheus)
          - [Grafana](https://github.com/grafana/grafana)
       - Cloud
          - [Datadog](https://www.datadoghq.com)
    - Logging
       - On-Premises
          - [ELK Stack](https://www.elastic.co/what-is/elk-stack)
          - [Seq](https://datalust.co/seq)
       - Cloud
          - [Datadog](https://docs.datadoghq.com/logs)
    - Tracing
       - On-Premises
          - [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-dotnet)
             - [Jaeger](https://github.com/jaegertracing/jaeger)
             - [Zipkin](https://github.com/openzipkin/zipkin)
       - Cloud
          - [Datadog](https://docs.datadoghq.com/tracing)
    - Alerting
       - On-Premises
          - [Zabbix](https://www.zabbix.com)
          - [Alertmanager](https://github.com/prometheus/alertmanager)
       - Cloud
          - [Datadog](https://docs.datadoghq.com/monitors)

20. Client-Side .NET
    - Template Engines
       - [Razor](https://docs.microsoft.com/aspnet/core/mvc/views/razor)
       - [DotLiquid](https://github.com/dotliquid/dotliquid)
       - [Scriban](https://github.com/lunet-io/scriban)
       - [Fluid](https://github.com/sebastienros/fluid)
    - Frameworks
       - [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
       - [.NET MAUI](https://github.com/dotnet/maui)

21. Good to Know
    - [MediatR](https://github.com/jbogard/MediatR)
    - [Fluent Validation](https://github.com/JeremySkinner/FluentValidation)
    - [Polly](https://github.com/App-vNext/Polly)
    - [Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet)
    - [NodaTime](https://github.com/nodatime/nodatime)
    - [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
    - [Nuke](https://github.com/nuke-build/nuke)
    - [EF Core Bulk Extensions](https://github.com/borisdj/EFCore.BulkExtensions)


## Wrap Up

If you think the roadmap can be improved, please do open a PR with any updates and submit any issues. Also, I will continue to improve this, so you might want to star this repository to revisit.

Idea from : [React Developer RoadMap](https://github.com/adam-golab/react-developer-roadmap)

## Contribution

Want to contribute? We encourage community feedback and contributions. Please follow our [contributing guidelines](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap/blob/master/CONTRIBUTING.md).

## Credits

### Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/AspNetCore-Developer-Roadmap#backer)]

<a href="https://github.com/sponsors/MoienTajik" target="_blank"><img src="https://opencollective.com/AspNetCore-Developer-Roadmap/backers.svg?width=890"></a>

### Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://github.com/sponsors/MoienTajik)]

<a href="https://github.com/sponsors/MoienTajik" target="_blank"><img src="https://opencollective.com/AspNetCore-Developer-Roadmap/sponsor/0/avatar.svg"></a>


## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0)
