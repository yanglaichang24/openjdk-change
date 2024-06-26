# JDK 9

本项目的目标是在Java社区过程中生成JSR379定义的Java SE 9平台的开源参考实现。

JDK 9于2017年9月21日正式上市。GPL下的生产就绪二进制文件可从Oracle获得；其他供应商的二进制文件将很快发布。

本次发布的特点和时间表是通过JEP流程提出和跟踪的，并经JEP 2.0提案修订。


## Features
+ 102: Process API Updates (ProcessHandle ProcessHandle提供了对本地进程的控制，可以监控其存活，查找其子进程，查看其信息，甚至销毁它。非常适合耗时较长的进程调用)
+ 110: HTTP 2 Client
+ 143: Improve Contended Locking
+ 158: Unified JVM Logging
+ 165: Compiler Control
+ 193: Variable Handles
+ 197: Segmented Code Cache
+ 199: Smart Java Compilation, Phase Two
+ 200: The Modular JDK
+ 201: Modular Source Code
+ 211: Elide Deprecation Warnings on Import Statements
+ 212: Resolve Lint and Doclint Warnings
+ 213: Milling Project Coin
+ 214: Remove GC Combinations Deprecated in JDK 8
+ 215: Tiered Attribution for javac
+ 216: Process Import Statements Correctly
+ 217: Annotations Pipeline 2.0
+ 219: Datagram Transport Layer Security (DTLS)
+ 220: Modular Run-Time Images
+ 221: Simplified Doclet API
+ 222: jshell: The Java Shell (Read-Eval-Print Loop)
+ 223: New Version-String Scheme
+ 224: HTML5 Javadoc
+ 225: Javadoc Search
+ 226: UTF-8 Property Files
+ 227: Unicode 7.0
+ 228: Add More Diagnostic Commands
+ 229: Create PKCS12 Keystores by Default
+ 231: Remove Launch-Time JRE Version Selection
+ 232: Improve Secure Application Performance
+ 233: Generate Run-Time Compiler Tests Automatically
+ 235: Test Class-File Attributes Generated by javac
+ 236: Parser API for Nashorn
+ 237: Linux/AArch64 Port
+ 238: Multi-Release JAR Files
+ 240: Remove the JVM TI hprof Agent
+ 241: Remove the jhat Tool
+ 243: Java-Level JVM Compiler Interface
+ 244: TLS Application-Layer Protocol Negotiation Extension
+ 245: Validate JVM Command-Line Flag Arguments
+ 246: Leverage CPU Instructions for GHASH and RSA
+ 247: Compile for Older Platform Versions
+ 248: Make G1 the Default Garbage Collector
+ 249: OCSP Stapling for TLS
+ 250: Store Interned Strings in CDS Archives
+ 251: Multi-Resolution Images
+ 252: Use CLDR Locale Data by Default
+ 253: Prepare JavaFX UI Controls & CSS APIs for Modularization
+ 254: Compact Strings
+ 255: Merge Selected Xerces 2.11.0 Updates into JAXP
+ 256: BeanInfo Annotations
+ 257: Update JavaFX/Media to Newer Version of GStreamer
+ 258: HarfBuzz Font-Layout Engine
+ 259: Stack-Walking API
+ 260: Encapsulate Most Internal APIs
+ 261: **Module System**
+ 262: TIFF Image I/O
+ 263: HiDPI Graphics on Windows and Linux
+ 264: Platform Logging API and Service
+ 265: Marlin Graphics Renderer
+ 266: More Concurrency Updates
+ 267: Unicode 8.0
+ 268: XML Catalogs
+ 269: Convenience Factory Methods for Collections
+ 270: Reserved Stack Areas for Critical Sections
+ 271: Unified GC Logging
+ 272: Platform-Specific Desktop Features
+ 273: DRBG-Based SecureRandom Implementations
+ 274: Enhanced Method Handles
+ 275: Modular Java Application Packaging
+ 276: Dynamic Linking of Language-Defined Object Models
+ 277: Enhanced Deprecation
+ 278: Additional Tests for Humongous Objects in G1
+ 279: Improve Test-Failure Troubleshooting
+ 280: Indify String Concatenation
+ 281: HotSpot C++ Unit-Test Framework
+ 282: jlink: The Java Linker
+ 283: Enable GTK 3 on Linux
+ 284: New HotSpot Build System
+ 285: Spin-Wait Hints
+ 287: SHA-3 Hash Algorithms
+ 288: Disable SHA-1 Certificates
+ 289: Deprecate the Applet API
+ 290: Filter Incoming Serialization Data
+ 291: Deprecate the Concurrent Mark Sweep (CMS) Garbage Collector
+ 292: Implement Selected ECMAScript 6 Features in Nashorn
+ 294: Linux/s390x Port
+ 295: Ahead-of-Time Compilation
+ 297: Unified arm32/arm64 Port
+ 298: Remove Demos and Samples
+ 299: Reorganize Documentation

## Schedule
+ 2016/05/26		Feature Complete
+ 2016/12/22		Feature Extension Complete
+ 2017/01/05		Rampdown Start
+ 2017/02/09		All Tests Run
+ 2017/02/16		Zero Bug Bounce
+ 2017/03/16		Rampdown Phase Two
+ 2017/06/22		Initial Release Candidate
+ 2017/07/06		Final Release Candidate
+ 2017/09/21		General Availability

## Phases

We stabilized the release in an increasingly-rigorous sequence of phases, listed here for the record:

+ Rampdown Phase One
+ Rampdown Phase Two
+ Release-Candidate Phase

During those phases we used three processes to coordinate our work:

+ Feature-Complete extension request process
+ Bug-deferral process (RDP 1 and later)
+ Fix-request process (RDP 2 and later)

## Milestone definitions

The milestone definitions for JDK 9 were the same as those for JDK 8, with the addition of:

+ Feature Extension Complete — The date by which JEPs and small enhancements that have been granted extensions via the FC extension-request process must be integrated into the master forest.

+ Initial Release Candidate — The date on which the first release candidate is built and submitted for testing