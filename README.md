# 📦 Awesome DotNet Packages [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

    A collection of awesome and top .NET packages sorted by most popular needs.

## Give a Star! ⭐️

If you liked this repository or find it useful, please give it a star. Thanks!

## Contents
- [Object Mapper](#object-mapper)
- [IoC](#ioc)
- [Task Scheduler/Background Job](#task-scheduler--background-job)
- [Serialization](#serialization)
- [Validation](#validation)
- [ORM](#orm)
- [NoSQL](#nosql)
- [Query Builder](#query-builder)
- [Messaging and Queue](#messaging-and-queue)
- [Http Client - REST](#http-client--rest)
- [Security](#security)
- [CSV, Excel, Word, and PDF](#csv-excel-word-and-pdf)
- [DateTime](#datetime)
- [Linq](#linq)
- [JWT](#jwt)
- [HtmlParser](#htmlparser)
- [Profiler](#Profling-Tracing-and-Metrics)
- [Caching](#caching)
- [Testing](#testing)
- [OpenAPI](#openapi)
- [Logging](#logging)
- [Console](#console)

## Libraries
<!--
	🟡 Recommended - 🟢 Good to know - 🟣 Other options / Possibilities
-->

### Object Mapper
- [**AutoMapper**](https://github.com/AutoMapper/AutoMapper) 
	> A convention-based object-object mapper in .NET

	[![GitHub Stars](https://img.shields.io/github/stars/AutoMapper/AutoMapper?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/AutoMapper/AutoMapper)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/AutoMapper?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/AutoMapper)

- [**Maspter**](https://github.com/MapsterMapper/Mapster)
	> A fast, fun and stimulating object to object Mapper

	[![GitHub Stars](https://img.shields.io/github/stars/MapsterMapper/Mapster?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/MapsterMapper/Mapster)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Mapster?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Mapster)

### IoC
- [**Autofac**](https://github.com/autofac/Autofac)
	> Autofac is an IoC container for .NET. It manages the dependencies between classes so that applications stay easy to change as they grow in size and complexity.

	[![GitHub Stars](https://img.shields.io/github/stars/autofac/Autofac?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/autofac/Autofac)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Autofac?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Autofac)

### Task Scheduler / Background Job
- [**HangFire**](https://github.com/HangfireIO/Hangfire)
	> An easy way to perform background job processing in your .NET and .NET Core applications. No Windows Service or separate process required.
	
	[![GitHub Stars](https://img.shields.io/github/stars/HangfireIO/Hangfire?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/HangfireIO/Hangfire)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Hangfire?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Hangfire)

- [**Quartz.NET**](https://github.com/quartznet/quartznet)
	> Quartz Enterprise Scheduler .NET

	[![GitHub Stars](https://img.shields.io/github/stars/quartznet/quartznet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/quartznet/quartznet)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Quartz?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Quartz)

- [**Coravel**](https://github.com/jamesmh/coravel)
	> Near-zero config .NET Core micro-framework that makes advanced application features like Task Scheduling, Caching, Queuing, Event Broadcasting, and more a breeze!

	[![GitHub Stars](https://img.shields.io/github/stars/jamesmh/coravel?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/jamesmh/coravel)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Coravel?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Coravel)

### Serialization
- Json Serializer
	- [**Newtonsoft.Json (Json.NET)**](https://github.com/JamesNK/Newtonsoft.Json)
		> Json .NET is a popular high-performance JSON framework for .NET

		[![GitHub Stars](https://img.shields.io/github/stars/JamesNK/Newtonsoft.Json?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/JamesNK/Newtonsoft.Json)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Newtonsoft.Json?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Newtonsoft.Json)

- Binary Serializer
	- [**MessagePack**](https://github.com/neuecc/MessagePack-CSharp)
		> Extremely Fast MessagePack (MsgPack) Serializer for .NET

		[![GitHub Stars](https://img.shields.io/github/stars/neuecc/MessagePack-CSharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/neuecc/MessagePack-CSharp)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MessagePack?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MessagePack)

	- [**Protobuf-Net**](https://github.com/protobuf-net/protobuf-net)
		> protobuf-net is a contract based serializer for .NET code, that happens to write data in the "protocol buffers" serialization format engineered by Google.
		
		[![GitHub Stars](https://img.shields.io/github/stars/protobuf-net/protobuf-net?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/protobuf-net/protobuf-net)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/protobuf-net?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/protobuf-net)

- XML Serializer
	- [**System.Xml.XmlSerializer**](https://docs.microsoft.com/en-us/dotnet/api/system.xml.serialization.xmlserializer)
		> Provides classes for serializing objects to the Extensible Markup Language (XML) and deserializing XML data to objects.
		
		[![NuGet Downloads](https://img.shields.io/nuget/dt/System.Xml.XmlSerializer?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/System.Xml.XmlSerializer)

### Validation
- [**FluentValidation**](https://github.com/FluentValidation/FluentValidation)
	> A popular .NET validation library for building strongly-typed validation rules.

	[![GitHub Stars](https://img.shields.io/github/stars/FluentValidation/FluentValidation?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/FluentValidation/FluentValidation)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/FluentValidation?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/FluentValidation)

### ORM 
- [**Entity Framework**](https://github.com/dotnet/ef6)
	> Entity Framework 6 (EF6) is an object-relational mapper that enables .NET developers to work with relational data using domain-specific objects. It eliminates the need for most of the data-access code that developers usually need to write.

	[![GitHub Stars](https://img.shields.io/github/stars/dotnet/ef6?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/dotnet/ef6)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/EntityFramework?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/EntityFramework)

- [**Entity Framework Core**](https://github.com/dotnet/efcore)
	> EF Core is a modern object-database mapper for .NET. It supports LINQ queries, change tracking, updates, and schema migrations.

	[![GitHub Stars](https://img.shields.io/github/stars/dotnet/efcore?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/dotnet/efcore)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Microsoft.EntityFrameworkCore?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore)

- [**Dapper**](https://github.com/StackExchange/Dapper)
	> Dapper - a simple object mapper for .NET

	[![GitHub Stars](https://img.shields.io/github/stars/StackExchange/Dapper?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/StackExchange/Dapper)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Dapper?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Dapper)

- [**linq2db**](https://github.com/linq2db/linq2db)
	> Linq to database provider.

	[![GitHub Stars](https://img.shields.io/github/stars/linq2db/linq2db?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/linq2db/linq2db)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/linq2db?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/linq2db)
	
### NoSQL
- [**MongoDb**](https://github.com/mongodb/mongo-csharp-driver)
	> The official MongoDB C#/.NET Driver provides asynchronous interaction with MongoDB.
	
	[![GitHub Stars](https://img.shields.io/github/stars/mongodb/mongo-csharp-driver?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/mongodb/mongo-csharp-driver)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/MongoDB.Driver?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MongoDB.Driver)

- [**Elastic**](https://github.com/elastic/elasticsearch-net)
	> Exposes all the Elasticsearch API endpoints but leaves you in control of building the request and response bodies. 

	[![GitHub Stars](https://img.shields.io/github/stars/elastic/elasticsearch-net?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/elastic/elasticsearch-net)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Elasticsearch.Net?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Elasticsearch.Net)

- [**StackExchange.Redis**](https://github.com/StackExchange/StackExchange.Redis)
	> High performance Redis client, incorporating both synchronous and asynchronous usage.
	
	[![GitHub Stars](https://img.shields.io/github/stars/StackExchange/StackExchange.Redis?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/StackExchange/StackExchange.Redis)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/StackExchange.Redis?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/StackExchange.Redis)

- [**LiteDB**](https://github.com/mbdavid/litedb)
	> LiteDB is a small, fast and lightweight .NET NoSQL embedded database.
	
	[![GitHub Stars](https://img.shields.io/github/stars/mbdavid/litedb?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/mbdavid/litedb)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/LiteDB?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/LiteDB)

### Query Builder
- [**SqlKata**](https://github.com/sqlkata/querybuilder)
	> SqlKata Query Builder is a powerful SQL Query Builder written in C#.
	
	[![GitHub Stars](https://img.shields.io/github/stars/sqlkata/querybuilder?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/sqlkata/querybuilder)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/SqlKata?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/SqlKata)

### Messaging and Queue
- Commands/Events Dispatcher
	- [**MediatR**](https://github.com/jbogard/MediatR)
		> Simple, unambitious mediator implementation in .NET
		
		[![GitHub Stars](https://img.shields.io/github/stars/jbogard/MediatR?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/jbogard/MediatR)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/mediatr?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/mediatr)

	- [**Brighter**](https://github.com/BrighterCommand/Brighter)
		> The Command Dispatcher pattern is an addition to the Command design pattern that decouples the dispatcher for a service from its execution.
		
		[![GitHub Stars](https://img.shields.io/github/stars/BrighterCommand/Brighter?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/BrighterCommand/Brighter)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/paramore.brighter?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/paramore.brighter)

- Message Bus
	- [**Confluent.Kafka**](https://github.com/confluentinc/confluent-kafka-dotnet)
		> Confluent's Apache Kafka .NET client.
		
		[![GitHub Stars](https://img.shields.io/github/stars/confluentinc/confluent-kafka-dotnet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/confluentinc/confluent-kafka-dotnet)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Confluent.Kafka?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Confluent.Kafka)

	- [**kafka-sharp**](https://github.com/criteo/kafka-sharp)
		> A .NET implementation of the Apache Kafka client side protocol geared toward performance (both throughput and memory wise). It is especially suited for scenarios where applications are streaming a large number of messages across a fair number of topics.
		
		[![GitHub Stars](https://img.shields.io/github/stars/criteo/kafka-sharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/criteo/kafka-sharp)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/kafka-sharp?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/kafka-sharp)

	- [**RabbitMQ.Client**](https://github.com/rabbitmq/rabbitmq-dotnet-client)
		> RabbitMQ .NET client
		
		[![GitHub Stars](https://img.shields.io/github/stars/rabbitmq/rabbitmq-dotnet-client?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/rabbitmq/rabbitmq-dotnet-client)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/RabbitMQ.Client?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/RabbitMQ.Client)

- Service Bus
	- [**MassTransit**](https://github.com/MassTransit/MassTransit)
		> MassTransit is a free, open-source distributed application framework for .NET. MassTransit makes it easy to create applications and services that leverage message-based, loosely-coupled asynchronous communication for higher availability, reliability, and scalability.
		
		[![GitHub Stars](https://img.shields.io/github/stars/MassTransit/MassTransit?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/MassTransit/MassTransit)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MassTransit?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MassTransit)

	- [**NServiceBus**](https://github.com/Particular/NServiceBus)
		> MassTransit is a free, open-source distributed application framework for .NET. MassTransit makes it easy to create applications and services that leverage message-based, loosely-coupled asynchronous communication for higher availability, reliability, and scalability.
		
		[![GitHub Stars](https://img.shields.io/github/stars/Particular/NServiceBus?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/Particular/NServiceBus)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NServiceBus?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NServiceBus)

### Http Client / REST
- [**Refit**](https://github.com/reactiveui/refit)
	> The automatic type-safe REST library for Xamarin and .NET

	[![GitHub Stars](https://img.shields.io/github/stars/reactiveui/refit?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/reactiveui/refit)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/Refit?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Refit)

- [**RestEase**](https://github.com/canton7/RestEase)
	> Easy-to-use typesafe REST API client library, which is simple and customisable.
	
	[![GitHub Stars](https://img.shields.io/github/stars/canton7/RestEase?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/canton7/RestEase)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/RestEase?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/RestEase)

- [**RestSharp**](https://github.com/restsharp/RestSharp)
	> Simple REST and HTTP API Client for .NET
	
	[![GitHub Stars](https://img.shields.io/github/stars/restsharp/RestSharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/restsharp/RestSharp)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/RestSharp?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/RestSharp)

### Security
- Security Libraries
	- [**NWebsec**](https://github.com/NWebsec/NWebsec)
		> NWebsec consists of several security libraries for ASP.NET applications.

		[![GitHub Stars](https://img.shields.io/github/stars/NWebsec/NWebsec?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/NWebsec/NWebsec)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NWebsec.AspNetCore.Core?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NWebsec.AspNetCore.Core)

- Authentication and Authorization
	- [**Microsoft.AspNetCore.Identity**](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity)
		> ASP.NET Core Identity is the membership system for building ASP.NET Core web applications, including membership, login, and user data. ASP.NET Core Identity allows you to add login features to your application and makes it easy to customize data about the logged in user.

		[![NuGet Downloads](https://img.shields.io/nuget/dt/Microsoft.AspNetCore.Identity?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Microsoft.AspNetCore.Identity)

	- [**IdentityServer4**](https://github.com/IdentityServer/IdentityServer4)
		> IdentityServer is a free, open source OpenID Connect and OAuth 2.0 framework for ASP.NET Core.

		[![GitHub Stars](https://img.shields.io/github/stars/IdentityServer/IdentityServer4?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/IdentityServer/IdentityServer4)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/IdentityServer4?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/IdentityServer4)

- Captcha
	- [**PaulMiami.AspNetCore.Mvc.Recaptcha**](https://github.com/PaulMiami/reCAPTCHA)
		> The reCAPTCHA 2.0 for ASPNET Core.

		[![GitHub Stars](https://img.shields.io/github/stars/PaulMiami/reCAPTCHA?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/PaulMiami/reCAPTCHA)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/PaulMiami.AspNetCore.Mvc.Recaptcha?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/PaulMiami.AspNetCore.Mvc.Recaptcha)

- Password Valdiator/Generator
	- [**PasswordGenerator**](https://github.com/prjseal/PasswordGenerator)
		> A library which generates random passwords with different settings to meet the OWASP requirements.

		[![GitHub Stars](https://img.shields.io/github/stars/prjseal/PasswordGenerator?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/prjseal/PasswordGenerator)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/PasswordGenerator?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/PasswordGenerator)

- Cryptography
	- [**Portable.BouncyCastle**](https://github.com/novotnyllc/bc-csharp)
		> A library which generates random passwords with different settings to meet the OWASP requirements.

		[![GitHub Stars](https://img.shields.io/github/stars/novotnyllc/bc-csharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/novotnyllc/bc-csharp)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Portable.BouncyCastle?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Portable.BouncyCastle)

### Compression
- Zip Compression
	- [**SharpZipLib**](https://github.com/icsharpcode/SharpZipLib)
		> #ziplib is a Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform.

		[![GitHub Stars](https://img.shields.io/github/stars/icsharpcode/SharpZipLib?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/icsharpcode/SharpZipLib)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/SharpZipLib?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/SharpZipLib)

- Compression Algorithms
	- [**Brotli.NET**](https://github.com/XieJJ99/brotli.net)
		> The .NET implementation of the brotli algorithm, provides similar interface to Google official API.

		[![GitHub Stars](https://img.shields.io/github/stars/XieJJ99/brotli.net?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/XieJJ99/brotli.net)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Brotli.NET?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Brotli.NET)

### CSV, Excel, Word, and PDF
- CSV
	- [**CsvHelper**](https://github.com/JoshClose/CsvHelper)
		> Library to help reading and writing CSV files

		[![GitHub Stars](https://img.shields.io/github/stars/JoshClose/CsvHelper?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/JoshClose/CsvHelper)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/CsvHelper?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/CsvHelper)

- Excel
	- [**EPPlus**](https://github.com/EPPlusSoftware/EPPlus)
		> Create advanced Excel spreadsheets using .NET

		[![GitHub Stars](https://img.shields.io/github/stars/EPPlusSoftware/EPPlus?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/EPPlusSoftware/EPPlus)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/EPPlus?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/EPPlus)

	- [**NPOI**](https://github.com/nissl-lab/npoi)
		> a .NET library that can read/write Office formats without Microsoft Office installed. No COM+, no interop.

		[![GitHub Stars](https://img.shields.io/github/stars/nissl-lab/npoi?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nissl-lab/npoi)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NPOI?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NPOI)

- Word
	- [**DocX**](https://github.com/xceedsoftware/DocX)
		> DocX is a .NET library that allows developers to manipulate Microsoft Word files, in an easy and intuitive manner. DocX is fast, lightweight and best of all it does not require Microsoft Word or Office to be installed.

		[![GitHub Stars](https://img.shields.io/github/stars/xceedsoftware/DocX?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/xceedsoftware/DocX)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/DocX?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/DocX)
	
	- [**NPOI**](https://github.com/nissl-lab/npoi)
		> a .NET library that can read/write Office formats without Microsoft Office installed. No COM+, no interop.

		[![GitHub Stars](https://img.shields.io/github/stars/nissl-lab/npoi?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nissl-lab/npoi)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NPOI?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NPOI)
	
- PDF
	- Reporting
		- [**FastReport**](https://github.com/FastReports/FastReport)
			> FastReport provides free open source report generator for .NET 5/.NET Core/.NET Framework. You can use the FastReport Open Source in MVC, Web API, console applications.

			[![GitHub Stars](https://img.shields.io/github/stars/FastReports/FastReport?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/FastReports/FastReport)
			[![NuGet Downloads](https://img.shields.io/nuget/dt/FastReport.OpenSource?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/FastReport.OpenSource/)
		
		- [**PdfReport.Core**](https://github.com/VahidN/PdfReport.Core)
			> PdfReport.Core is a code first reporting engine, which is built on top of the iTextSharp.LGPLv2.Core and EPPlus.Core libraries
			
			[![GitHub Stars](https://img.shields.io/github/stars/VahidN/PdfReport.Core?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/VahidN/PdfReport.Core)
			[![NuGet Downloads](https://img.shields.io/nuget/dt/PdfRpt.Core?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/PdfRpt.Core/)
	
	- Renderers
		- [**DinkToPdf**](https://github.com/rdvojmoc/DinkToPdf)
			> .NET Core P/Invoke wrapper for wkhtmltopdf library that uses Webkit engine to convert HTML pages to PDF.

			[![GitHub Stars](https://img.shields.io/github/stars/rdvojmoc/DinkToPdf?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/rdvojmoc/DinkToPdf)
			[![NuGet Downloads](https://img.shields.io/nuget/dt/DinkToPdf?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/DinkToPdf)

	- Create, Edit and Extract
		- [**itext7**](https://github.com/itext/itext7-dotnet)
			> iText 7 allows you to build custom PDF scenarios for web, mobile, desktop or cloud apps in .NET.

			[![GitHub Stars](https://img.shields.io/github/stars/itext/itext7-dotnet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/itext/itext7-dotnet)
			[![NuGet Downloads](https://img.shields.io/nuget/dt/itext7?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/itext7)
	
### DateTime
- [**NodaTime**](https://github.com/nodatime/nodatime)
	> A better date and time API for .NET

	[![GitHub Stars](https://img.shields.io/github/stars/nodatime/nodatime?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nodatime/nodatime)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/NodaTime?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NodaTime)

### Linq
- [**MoreLinq**](https://github.com/morelinq/MoreLINQ)
	> Extensions to LINQ to Objects.

	[![GitHub Stars](https://img.shields.io/github/stars/morelinq/MoreLINQ?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/morelinq/MoreLINQ)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/morelinq?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/morelinq)

### JWT

### HtmlParser
- [**HtmlAgilityPack**](https://github.com/zzzprojects/html-agility-pack)
	> HAP is an HTML parser written in C# to read/write DOM and supports plain XPATH or XSLT.
	
	[![GitHub Stars](https://img.shields.io/github/stars/zzzprojects/html-agility-pack?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/zzzprojects/html-agility-pack)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/HtmlAgilityPack?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/HtmlAgilityPack)

- [**AngleSharp**](https://github.com/AngleSharp/AngleSharp)
	> The ultimate angle brackets parser library parsing HTML5, MathML, SVG and CSS to construct a DOM based on the official W3C specifications.
	
	[![GitHub Stars](https://img.shields.io/github/stars/AngleSharp/AngleSharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/AngleSharp/AngleSharp)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/AngleSharp?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/AngleSharp)

### Profling, Tracing, and Metrics
- Profiling/Monitoring
	- [**MiniProfiler**](https://github.com/MiniProfiler/dotnet)
		> A simple but effective mini-profiler for ASP.NET (and Core) websites.

		[![GitHub Stars](https://img.shields.io/github/stars/MiniProfiler/dotnet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/MiniProfiler/dotnet)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MiniProfiler.AspNetCore.Mvc?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MiniProfiler.AspNetCore.Mvc)

- Tracing
	- [**prometheus-net**](https://github.com/prometheus-net/prometheus-net)
		> .NET library to instrument your code with Prometheus metrics.

		[![GitHub Stars](https://img.shields.io/github/stars/prometheus-net/prometheus-net?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/prometheus-net/prometheus-net)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/prometheus-net?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/prometheus-net)
	
- Metrics
	- [**App.Metrics**](https://github.com/AppMetrics/AppMetrics)
		> App Metrics is an open-source and cross-platform .NET library used to record and report metrics within an application.

		[![GitHub Stars](https://img.shields.io/github/stars/AppMetrics/AppMetrics?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/AppMetrics/AppMetrics)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/App.Metrics?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/App.Metrics)

### Caching
- InMemory
	- [**Microsoft.Extensions.Caching.Memory**](https://docs.microsoft.com/aspnet/core/performance/caching/memory)
		> In-memory cache implementation of Microsoft.Extensions.Caching.Memory.IMemoryCache.

		[![NuGet Downloads](https://img.shields.io/nuget/dt/Microsoft.Extensions.Caching.Memory?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Microsoft.Extensions.Caching.Memory)

- Distributed
	- [**StackExchange.Redis**](https://github.com/StackExchange/StackExchange.Redis)
		> High performance Redis client, incorporating both synchronous and asynchronous usage.
	
		[![GitHub Stars](https://img.shields.io/github/stars/StackExchange/StackExchange.Redis?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/StackExchange/StackExchange.Redis)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/StackExchange.Redis?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/StackExchange.Redis)

	- [**ServiceStack.Redis**](https://github.com/ServiceStack/ServiceStack.Redis)
		> ServiceStack Redis Client is a simple, high-performance and feature-rich Client for Redis with native support and high-level abstractions for serializing POCOs and Complex Types.
	
		[![GitHub Stars](https://img.shields.io/github/stars/ServiceStack/ServiceStack.Redis?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/ServiceStack/ServiceStack.Redis)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/ServiceStack.Redis?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/ServiceStack.Redis) 

- Caching Frameworks
	- [**CacheManager.Core**](https://github.com/MichaCo/CacheManager)
		> CacheManager is an open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features.

		[![GitHub Stars](https://img.shields.io/github/stars/MichaCo/CacheManager?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/MichaCo/CacheManager)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/CacheManager.Core?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/CacheManager.Core)

- Second Level Cache
	- [**EF Core Second Level Cache Interceptor**](https://github.com/VahidN/EFCoreSecondLevelCacheInterceptor)
		> Entity Framework Core Second Level Caching Library.

		[![GitHub Stars](https://img.shields.io/github/stars/VahidN/EFCoreSecondLevelCacheInterceptor?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/VahidN/EFCoreSecondLevelCacheInterceptor)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/EFCoreSecondLevelCacheInterceptor?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/EFCoreSecondLevelCacheInterceptor)

### Testing
- Test Frameworks
	- [**xUnit**](https://github.com/xunit/xunit)
		> xUnit is a developer testing framework, built to support Test Driven Development, with a design goal of extreme simplicity and alignment with framework features.

		[![GitHub Stars](https://img.shields.io/github/stars/xunit/xunit?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/xunit/xunit)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/xunit?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/xunit)
	
	- [**NUnit**](https://github.com/nunit/nunit)
		> NUnit is a unit-testing framework for all .NET languages.

		[![GitHub Stars](https://img.shields.io/github/stars/nunit/nunit?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nunit/nunit)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NUnit?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NUnit)
		
	- [**MyTested.AspNetCore.Mvc**](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc)
		> MyTested.AspNetCore.Mvc is a strongly-typed unit testing library providing an easy fluent interface to test the ASP.NET Core framework, perfectly suitable for 			both MVC and API scenarios. It is testing framework agnostic so that you can combine it with a test runner of your choice (e.g. xUnit, NUnit, etc.).

		[![GitHub Stars](https://img.shields.io/github/stars/ivaylokenov/MyTested.AspNetCore.Mvc?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MyTested.AspNetCore.Mvc?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MyTested.AspNetCore.Mvc/)

- Asserations
	- [**FluentAssertions**](https://github.com/fluentassertions/fluentassertions)
		> A very extensive set of extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style unit tests. 

		[![GitHub Stars](https://img.shields.io/github/stars/fluentassertions/fluentassertions?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/fluentassertions/fluentassertions)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/FluentAssertions?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/FluentAssertions)

- Mocking
	- [**Moq**](https://github.com/moq/moq4)
		> The most popular and friendly mocking library for .NET

		[![GitHub Stars](https://img.shields.io/github/stars/moq/moq4?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/moq/moq4)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Moq?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Moq)

	- [**FakeItEasy**](https://github.com/FakeItEasy/FakeItEasy)
		> A .NET dynamic fake library for creating all types of fake objects, mocks, stubs etc.
		
		[![GitHub Stars](https://img.shields.io/github/stars/FakeItEasy/FakeItEasy?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/FakeItEasy/FakeItEasy)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/FakeItEasy?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/FakeItEasy)
	
	- [**NSubstitute**](https://github.com/nsubstitute/NSubstitute)
		> A friendly substitute for .NET mocking libraries.

		[![GitHub Stars](https://img.shields.io/github/stars/nsubstitute/NSubstitute?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nsubstitute/NSubstitute)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NSubstitute?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NSubstitute)

- Fixture - Data Generator
	- [**AutoFixture**](https://github.com/AutoFixture/AutoFixture)
		> AutoFixture makes it easier for developers to do Test-Driven Development by automating non-relevant Test Fixture Setup, allowing the Test Developer to focus on the essentials of each test case.
		
		[![GitHub Stars](https://img.shields.io/github/stars/AutoFixture/AutoFixture?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/AutoFixture/AutoFixture)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/AutoFixture?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/AutoFixture)
	
	- [**NBuilder**](https://github.com/nbuilder/nbuilder)
		> Through a fluent, extensible interface, NBuilder allows you to rapidly create test data, automatically assigning values to properties and public fields that are one of the built in .NET data types (e.g. ints and strings). NBuilder allows you to override for properties you are interested in using lambda expressions.
		
		[![GitHub Stars](https://img.shields.io/github/stars/nbuilder/nbuilder?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/nbuilder/nbuilder)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/nbuilder?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/nbuilder)

- Helpers
	- [**Respawn**](https://github.com/jbogard/Respawn)
		> Respawn is a small utility to help in resetting test databases to a clean state. Instead of deleting data at the end of a test or rolling back a transaction, Respawn resets the database back to a clean checkpoint by intelligently deleting data from tables.
		
		[![GitHub Stars](https://img.shields.io/github/stars/jbogard/Respawn?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/jbogard/Respawn)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Respawn?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Respawn)

- HttpClient Mocking
	- [**RichardSzalay.MockHttp**](https://github.com/richardszalay/mockhttp)
		> MockHttp is a testing layer for Microsoft's HttpClient library. It allows stubbed responses to be configured for matched HTTP requests and can be used to test your application's service layer.
		
		[![GitHub Stars](https://img.shields.io/github/stars/richardszalay/mockhttp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/richardszalay/mockhttp)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/RichardSzalay.MockHttp?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/RichardSzalay.MockHttp)

- EF/Queryable Mocking
	- [**Effort.EF6**](https://github.com/zzzprojects/EntityFramework-Effort)
		> Effort is a powerful tool that enables a convenient way to create automated tests for Entity Framework based applications. [Learn more](https://entityframework-effort.net)

		[![GitHub Stars](https://img.shields.io/github/stars/zzzprojects/EntityFramework-Effort?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/zzzprojects/EntityFramework-Effort)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Effort.EF6?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Effort.EF6)

	- [**MockQueryable**](https://github.com/romantitov/MockQueryable)
		> Moking Entity Framework Core operations such as ToListAsync, FirstOrDefaultAsync etc.

		[![GitHub Stars](https://img.shields.io/github/stars/romantitov/MockQueryable?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/romantitov/MockQueryable)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/MockQueryable.Core?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/MockQueryable.Core)

- Temp Database
	- [**EfCore.TestSupport**](https://github.com/JonPSmith/EfCore.TestSupport)
		> Tools for helping in unit testing applications that use Entity Framework Core.

		[![GitHub Stars](https://img.shields.io/github/stars/JonPSmith/EfCore.TestSupport?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/JonPSmith/EfCore.TestSupport)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/EfCore.TestSupport?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/EfCore.TestSupport)

	- [**Mongo2Go**](https://github.com/Mongo2Go/Mongo2Go)
		> MongoDB for integration tests (.NET Core)

		[![GitHub Stars](https://img.shields.io/github/stars/Mongo2Go/Mongo2Go?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/Mongo2Go/Mongo2Go)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Mongo2Go?label=Downloads&logo=nuget&cacheSeconds=3600)](https://nuget.org/packages/Mongo2Go)

- Log Testing
	- [**Serilog.Sinks.XUnit**](https://github.com/trbenning/serilog-sinks-xunit)
		> The xunit test output sink for Serilog.

		[![GitHub Stars](https://img.shields.io/github/stars/trbenning/serilog-sinks-xunit?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/trbenning/serilog-sinks-xunit)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Serilog.Sinks.XUnit?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Serilog.Sinks.XUnit)

- Snapshot Testing
	- [**Snapshooter**](https://github.com/SwissLife-OSS/snapshooter)
		> Snapshooter is a flexible snapshot testing tool to simplify the result validation in your unit tests in .NET

		[![GitHub Stars](https://img.shields.io/github/stars/SwissLife-OSS/snapshooter?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/SwissLife-OSS/snapshooter)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Snapshooter?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Snapshooter)

- BDD Testing
	- [**SpecFlow**](https://github.com/SpecFlowOSS/SpecFlow)
		> SpecFlow is a pragmatic BDD solution for .NET. It provides test automation for .NET (.NET Framework, .NET Core and Mono), based on the Gherkin specification language and integrates to Visual Studio.

		[![GitHub Stars](https://img.shields.io/github/stars/SpecFlowOSS/SpecFlow?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/SpecFlowOSS/SpecFlow)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/SpecFlow?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/SpecFlow)

- UI Testing
	- [**Selenium.WebDriver**](https://github.com/SeleniumHQ/selenium)
		> Selenium is a set of different software tools each with a different approach to supporting browser automation. These tools are highly flexible, allowing many options for locating and manipulating elements within a browser, and one of its key features is the support for automating multiple browser platforms.
		
		[![GitHub Stars](https://img.shields.io/github/stars/SeleniumHQ/selenium?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/SeleniumHQ/selenium)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Selenium.WebDriver?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Selenium.WebDriver)

	- [**Puppeteer Sharp**](https://github.com/hardkoded/puppeteer-sharp)
		>  Headless Chrome .NET API

		[![GitHub Stars](https://img.shields.io/github/stars/hardkoded/puppeteer-sharp?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/hardkoded/puppeteer-sharp)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/PuppeteerSharp?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/PuppeteerSharp)

- Code Coverage
	- [**Coverlet**](https://github.com/coverlet-coverage/coverlet)
		>  Cross platform code coverage for .NET

		[![GitHub Stars](https://img.shields.io/github/stars/coverlet-coverage/coverlet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/coverlet-coverage/coverlet)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/coverlet.collector?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/coverlet.collector)

- XUnit Extensions\Helpers
	- [**xunit.analyzers**](https://github.com/xunit/xunit.analyzers)
		> Code Analyzers for projects using xUnit.net that help find and fix frequent issues when writing tests.

		[![GitHub Stars](https://img.shields.io/github/stars/xunit/xunit.analyzers?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/xunit/xunit.analyzers)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/xunit.analyzers?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/xunit.analyzers)

	- [**xunit.categories**](https://github.com/brendanconnolly/Xunit.Categories)
		> Friendlier attributes to help categorize your tests.

		[![GitHub Stars](https://img.shields.io/github/stars/brendanconnolly/Xunit.Categories?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/brendanconnolly/Xunit.Categories)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/xunit.categories?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/xunit.categories)

### OpenAPI
- [**Swagger (Swashbuckle)**](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
	> Swagger tooling for API's built with ASP.NET Core. Generate beautiful API documentation, including a UI to explore and test operations, directly from your routes, controllers and models.
	
	[![GitHub Stars](https://img.shields.io/github/stars/domaindrivendev/Swashbuckle.AspNetCore?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/swashbuckle.aspnetcore?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/swashbuckle.aspnetcore)

- [**NSwag**](https://github.com/RicoSuter/NSwag)
	> The OpenAPI/Swagger API toolchain for .NET and TypeScript.

	[![GitHub Stars](https://img.shields.io/github/stars/RicoSuter/NSwag?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/RicoSuter/NSwag)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/NSwag.AspNetCore?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NSwag.AspNetCore)

### Logging
- Logging libraries
	- [**Serilog**](https://github.com/serilog/serilog)
		> Serilog is a diagnostic logging library for .NET applications. It is easy to set up, has a clean API, and runs on all recent .NET platforms.
		
		[![GitHub Stars](https://img.shields.io/github/stars/serilog/serilog?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/serilog/serilog)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/serilog?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/serilog)

	- [**NLog**](https://github.com/NLog/NLog)
		> NLog is a free logging platform for .NET with rich log routing and management capabilities. It makes it easy to produce and manage high-quality logs for your application regardless of its size or complexity.

		[![GitHub Stars](https://img.shields.io/github/stars/NLog/NLog?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/NLog/NLog)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/NLog?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/NLog)

- Logging Management
	- [**Sentry**](https://github.com/getsentry/sentry-dotnet)
		> Open-source error tracking that helps developers monitor and fix crashes in real time.

		[![GitHub Stars](https://img.shields.io/github/stars/getsentry/sentry-dotnet?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/getsentry/sentry-dotnet)
		[![NuGet Downloads](https://img.shields.io/nuget/dt/Sentry?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/Sentry)

### Console
- [**Spectre.Console**](https://github.com/spectresystems/spectre.console)
	> A library that makes it easier to create beautiful, cross platform, console applications.
	
	[![GitHub Stars](https://img.shields.io/github/stars/spectresystems/spectre.console?label=Stars&logo=github&cacheSeconds=3600)](https://github.com/spectresystems/spectre.console)
	[![NuGet Downloads](https://img.shields.io/nuget/dt/spectre.console?label=Downloads&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/spectre.console)

## Contribution
Contributions are always welcome! Feel free to open an [issue][issues] or create a pull request.

## License
[![CC0][license-badge]][license]

To the extent possible under law, [Mohammad Javad Ebrahimi](https://github.com/mjebrahimi) has waived all copyright and related or neighboring rights to this work.

[issues]: https://github.com/mjebrahimi/Awesome-DotNet-Packages/issues/new
[license]: https://creativecommons.org/publicdomain/zero/1.0
[license-badge]: https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg
