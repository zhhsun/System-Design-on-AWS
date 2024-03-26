## 第一部分 系统设计基础

本单元为您提供了系统设计的坚实基础，提供了对支持所有类型软件系统的基本原则的见解，范围从权衡到选择正确的工具和技术的标准，从而，正确的体系结构模式。

本单元结束时，您将了解:

- 在大规模分布式系统中自然出现的系统权衡。
- 如何为数据存储做出正确的选择，从文件、块、对象存储到数据库，包括关系和非关系数据库。
- 如何使用缓存和cdn来支持存储和计算的大吞吐量和低延迟。
- 如何使用负载平衡器、API网关和反向代理水平扩展系统。
- 在OSI和TCP/IP模型的不同层的不同通信和网络协议之间的选择，以及如何选择何时使用什么。
- 常见的系统设计体系结构模式(在行业中常用)以及如何使其适应其技术体系结构。
- 映射到不同系统设计范式的不同AWS服务，我们将在后面的章节中进一步探讨。

本单元的前八章将涵盖:

1. 第1章将深入探讨大规模分布式系统中的权衡问题。我们将探讨一些基本概念，如可靠性、可伸缩性和可维护性，阐明为什么会出现这些权衡。我们将通过分布式计算的谬误来解决常见的误解，并解决关键的选择，如空间与时间、延迟与吞吐量、性能与可伸缩性、一致性与可用性。此外，我们将提供从多年的系统设计智慧中产生的实用指导方针和策略，提供切实可行的方法来增强系统性能和效率。
2. 第2章将介绍不同类型的数据存储类型，包括文件存储、块存储和对象存储。我们将在本章中介绍关系数据库、它们的概念和体系结构。您将深入了解扩展关系数据库的复杂性，包括分区、索引、复制、联合、分片和非规范化等技术。
3. 第3章将揭示非关系数据库的架构，如键值数据库、宽列数据库、文档数据库和图形数据库，以及无领导架构如何通过仲裁和一致哈希等机制实现可扩展性。
4. 第4章将向您介绍缓存，在这里我们将探索从客户端和服务器到应用程序和数据库级别的不同缓存策略。我们将剖析核心缓存方法，如透写、透读、提前刷新、回写和缓存旁边。此外，我们将揭示内容分发网络(cdn)的潜力——包括推式和拉式cdn——并演示它们如何利用边缘位置来减少延迟和优化内容分发。
5. 第5章将探讨垂直和水平扩展，阐明扩展计算资源的各种方法。负载平衡器、API网关和反向代理将占据中心位置，同时还将讨论L4网络扩展和L7应用层扩展。当我们深入研究创建可伸缩和弹性架构的细微差别时，故障转移策略、粘性会话和反向代理等概念将变得生动起来。
6. 第6章揭开了网络协议的神秘面纱，揭示了TCP/IP、UDP、HTTP、RMTP、XMPP的复杂性，以及它们的合适应用。您将全面了解同步和异步服务设计，并深入了解SOAP、REST、GRPC和GraphQL等标准。通过掌握这些通信概念，您将能够更好地为不同的用例做出明智的选择。
7. 第7章是关于容器化的——镜像的部署和Docker容器的编排。无服务器架构的概念也将出现，同时还将讨论微服务及其设计原则。在本章结束时，您将精通容器、微服务和无服务器架构的复杂世界。
8. 第8章详细讨论了编排，其中我们探讨了异步体系结构、消息代理、消息队列和发布者-订阅者模式。当您深入研究大规模软件工程设计时，您将比较微服务与单片设计、无服务器架构、saga模式、事件源模式、lambda架构、kappa架构和领域驱动设计。编排和编舞之间错综复杂的舞蹈将被揭开，引导您通过设计健壮和适应性强的系统的复杂性。

通过本单元对系统设计细微差别的全面学习，你将为运用这些原则和技术来创建高效的大型系统做好充分准备。

稍后，第2部分将详细介绍AWS服务，介绍这些概念的使用和权衡。