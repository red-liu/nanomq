# Introduction

[NanoMQ](https://nanomq.io/) is an open source project for edge computing that released in Jan 2021 and is the next generation of lightweight, high-performance **MQTT** messaging broker for the IoT edge computing scenario.

Github repository address: <https://github.com/emqx/nanomq>

[NanoMQ](https://nanomq.io/) aims to deliver simple and powerful message-centric services for different edge computing platforms; strives to remove the gap between hardware development and cloud computing; connects the physical world and digital intelligence from the open source community; thus popularizing edge computing applications and helping to connect everything.

**NanoMQ** in collaboration with **NNG**. Relying on **NNG**'s excellent network API design, **NanoMQ** can focus on **MQTT** broker performance and more extended features.The goal is to provide better SMP support and high performance-price ratio in edge devices and MECs. There are plans to add other IOT protocols such as ZMQ, NanoMSG and SP in the future.

**NanoMQ** currently has the following functions and features:

- Full support for the **MQTT 3.1.1** & **MQTT 5.0** protocol. 
- High compatibility and portability as the project relies only on the native **POSIX API** and is developed purely in C.
- **NanoMQ** is internally fully asynchronous IO and multi-threaded parallelism, so there is good support for SMP while achieving low latency and high throughput.
- It is cost-effective in terms of resource usage and is suitable for all types of edge computing platforms.

[Features](./features.md)

[Quick Start](./quick-start.md)

[Configuration](./config-description/v014.md)

[Build Options](./build-options.md)

[HTTP APIs](./http-api/v4.md)

[Web Hook](./web-hook.md)

[Toolkit](./toolkit.md)

[Test Report](./test-report.md)

[ZMQ Gateway](./zmq-gateway.md)