# JDK10

JDK10是JSR383在Java社区过程中定义的Java SE 10平台的开源参考实现。

JDK 10于2018年3月20日正式上市。GPL下的生产就绪二进制文件可从Oracle获得；其他供应商的二进制文件将很快发布。

本次发布的特点和时间表是通过JEP流程提出和跟踪的，并经JEP 2.0提案修订。


### Features
+ 286: Local-Variable Type Inference
+ 296: Consolidate the JDK Forest into a Single Repository
+ 304: Garbage-Collector Interface
+ 307: Parallel Full GC for G1
+ 310: Application Class-Data Sharing
+ 312: Thread-Local Handshakes
+ 313: Remove the Native-Header Generation Tool (javah)
+ 314: Additional Unicode Language-Tag Extensions
+ 316: Heap Allocation on Alternative Memory Devices
+ 317: Experimental Java-Based JIT Compiler
+ 319: Root Certificates
+ 322: Time-Based Release Versioning

### Schedule
+ 2017/12/14		Rampdown Phase One
+ 2018/01/11		All Tests Run
+ 2018/01/18		Rampdown Phase Two
+ 2018/02/08		Initial Release Candidate
+ 2018/02/22		Final Release Candidate
+ 2018/03/20		General Availability

### Phases
We stabilized the release in an increasingly-rigorous sequence of phases, listed here for the record:

+ Rampdown Phase One
+ Rampdown Phase Two
+ Release-Candidate Phase

During those phases we used three processes to coordinate our work:

+ Bug-deferral process (RDP 1 and later)
+ Late-enhancement request request process
+ Fix-request process (RDP 2 and later)