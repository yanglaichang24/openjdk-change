# JDK 11
JDK 11 is the open-source reference implementation of version 11 of the Java SE Platform as specified by by JSR 384 in the Java Community Process.

JDK 11 reached General Availability on 25 September 2018. Production-ready binaries under the GPL are available from Oracle; binaries from other vendors will follow shortly.

The features and schedule of this release were proposed and tracked via the JEP Process, as amended by the JEP 2.0 proposal. The release was produced using the JDK Release Process (JEP 3).

## Features
+ 181: **Nest-Based Access Control**(嵌套访问控制,class 新增方法getNestHost)
+ 309: **Dynamic Class-File Constants** (常量池增加新的格式CONSTANT_Dynamic)
+ 315: Improve Aarch64 Intrinsics
+ 318: **Epsilon: A No-Op Garbage Collector** (Epsilon 垃圾回收器,开发一个处理内存分配但不实现任何内存回收的GC,内存用完JVM退出)
+ 320: **Remove the Java EE and CORBA Modules**
+ 321: **HTTP Client (Standard)** (java.net.http.HttpClient)
+ 323: **Local-Variable Syntax for Lambda Parameters** (Lambda表达式支持 var)
+ 324: **Key Agreement with Curve25519 and Curve448**(新增加密算法Curve25519,Curve448)
+ 327: **Unicode 10**   (支持Unicode 10编码)
+ 328: Flight Recorder (分析记录器分析工具  -XX: StatFlightRecording)
+ 329: ChaCha20 and Poly1305 Cryptographic Algorithms ((新增加密算法ChaCha20,Poly1305))
+ 330: Launch Single-File Source-Code Programs (这个功能允许你直接使用java解析器运行java代码，java文件会在内存中执行编译并且直接执行。唯一的约束在于所有相关的类必须定义在东一个java文件中 执行 java xxx.java)
+ 331: Low-Overhead Heap Profiling (低负载堆分析JVMTI)
+ 332: **Transport Layer Security (TLS) 1.3** (升级TLS 1.3)
+ 333: **ZGC: A Scalable Low-Latency Garbage Collector(ZGC)**
(Experimental)
+ 335: Deprecate the Nashorn JavaScript Engine
+ 336: Deprecate the Pack200 Tools and API

## Schedule
+ 2018/06/28		Rampdown Phase One (fork from main line)
+ 2018/07/26		Rampdown Phase Two
+ 2018/08/16		Initial Release Candidate
+ 2018/08/30		Final Release Candidate
+ **2018/09/25		General Availability**
