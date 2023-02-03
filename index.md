---
layout: page
---

<div style="width: 100%; display: inline-block;">
<img src="{{ site.baseurl }}/public/ryan-stutsman.jpg" alt="Headshot" width="25%" style="float: left;"/>
<div style="float: left; padding-left: 20px;">
<span style="font-size: 150%;">Ryan Stutsman</span><br>
Associate Professor<br>
University of Utah<br>
<a href="mailto:stutsman@cs.utah.edu">stutsman@cs.utah.edu</a><br>
<a href="{{ site.baseurl }}/public/cv-stutsman.pdf">Curriculum Vitæ</a>
</div>
</div>

<p></p>

[Curriculum Vitæ]({{ site.baseurl }}/public/cv-stutsman.pdf) -
[Teaching](#teaching) -
[Projects](#projects) -
[Publications](#publications) -
[Activities](#activities)
<!--[Blog](./blog/)-->

<!--
*I am looking for Ph.D. students in the data center, cloud, and large-scale
storage area. If you are an admitted or current University of Utah CS student
feel free to contact me. Otherwise, apply to the [Utah SoC PhD
program](http://www.cs.utah.edu).*
-->

I am an Associate Professor and head of the [Scalable Software Systems Lab](http://www.utah.systems/)
in the [School of Computing](http://www.cs.utah.edu/)
at the [University of Utah](http://www.utah.edu/).
My interests include Distributed Systems,
Operating Systems, and Databases.  I'm passionate about designing and building
systems that allow large-scale applications to access data more intensively
than has been possible in the past.
Formerly, I was a Postdoctoral Researcher in the
[databases group](http://research.microsoft.com/en-us/groups/db/) at
[Microsoft Research](http://research.microsoft.com/).
Before that, I earned my Ph.D. at Stanford University working as a part of the
[RAMCloud](http://ramcloud.stanford.edu/) and the
[Secure Computer Systems](http://www.scs.stanford.edu/) labs.
<!--
My dissertation work,
[Fast Crash Recovery in RAMCloud](http://www.stanford.edu/~ouster/cgi-bin/papers/ramcloud-recovery.pdf)
provides durability and availability in a large-scale distributed DRAM-based
storage system with the same price and energy consumption as today's volatile
caches.  Overall, it enables the use of DRAM as fault-tolerant large-scale data
center storage which is 50 to 5,000 times faster than other data center storage
systems.
-->


# <a name="students"></a> Students

 - Current
   - James McMahon, PhD 2027 expected
   - Amit Samanta, PhD 2024 expected
   - Ankit Bhardwaj, PhD 2023 expected
   - Md Ashfaqur Rahaman, PhD 2026 expected
   - Todd Thornley, MS 2022 expected
 - Alumni
   - Vinita Pawar, MS 2022 expected
   - Tian Zhang, PhD 2021, now at Google
   - Chinmay Kulkarni, PhD 2021, now at Lightstep
   - Mohammed Al-Mahfoudh, PhD 2021
   - Meghana Gupta, MS 2021
   - Emerson Ford, BS 2021, now at Meta
   - Akshay Singh, MS 2020
   - Mazhar Naqvi, MS 2019, now at Microsoft
   - Paridhi Baheti, MS 2019, now at Microsoft
   - Aaron Langford, BS 2018, now at Instructure
   - Sara Moore (Adamson), BS 2018, now at InsideSales
   - Daniel Rushton, BS 2018, now at Nvidia
   - Aniraj Kesavan, MS 2017, now at LinkedIn

# <a name="teaching"></a> Teaching

- [CS6450 Fall 2022 - Distributed Systems](https://utah.instructure.com/courses/794856)
- [CS5460/6460 Spring 2022 - Operating Systems](https://utah.instructure.com/courses/756700)
- [CS5460/6460 Spring 2021 - Operating Systems](https://utah.instructure.com/courses/663531)
- [CS6450 Fall 2020 - Distributed Systems](https://utah.instructure.com/courses/635986)
- [CS5460/6460 Spring 2020 - Operating Systems](https://utah.instructure.com/courses/601363)
- [CS6465 Fall 2019 - Advanced Operating Systems](https://utah.instructure.com/courses/573975)
- [CS5460/6460 Spring 2019 - Operating Systems](https://utah.instructure.com/courses/539884)
- [CS6450 Fall 2018 - Distributed Systems](http://www.cs.utah.edu/~stutsman/cs6450/)
- [CS5460/6460 Spring 2018 - Operating Systems](https://utah.instructure.com/courses/475520)
- [CS6450 Fall 2017 - Distributed Systems](http://www.cs.utah.edu/~stutsman/cs6450/)
- [CS6963 Fall 2016 - Distributed Systems](http://www.cs.utah.edu/~stutsman/cs6963/)
- [CS5460/6460 Spring 2016 - Operating Systems](http://utah.instructure.com/courses/364658)
  - 2016-2017 University of Utah School of Computing Outstanding Teaching Award.
- [CS6963 Fall 2015 - Distributed Systems](http://www.cs.utah.edu/~stutsman/cs6963/)

# <a name="projects"></a> Projects

 - [NrOS](http://nrkernel.systems/) - NrOS is a new multikernel operating system
   that uses simple sequential data structures which are scaled in a black-box
   fashion to support many cores and NUMA sockets using node replication.
 - [Splinter](http://utah.systems/projects/splinter/) - A multi-tenant
   in-memory key-value store that operates on microsecond time scales with
   millions of operation per second while letting mutually distrusting tenants
   push extensions to it at runtime to customize its operations and data model.
 - [RAMCloud](http://ramcloud.stanford.edu/) - A high-performance distributed
   key-value storage system designed with latency goals to enable the next
   generation of data center applications.
 - [Deuteronomy](http://research.microsoft.com/en-us/groups/db/) - A fully lock-free
   transactional database engine that is performance competitive with modern
   in-memory databases. Deuteronomy maintains clean architectural separation of
   storage, indexing, and transaction components for flexible
   deployment in embedded, cloud, or data center systems.
 - [Cinder](http://www.scs.stanford.edu/cinder) - An operating system designed
   for cellular phones and mobile devices with fine-grained energy accounting,
    allocation, subdivision, and delegation.
 - [HiStar](http://www.scs.stanford.edu/histar) - An operating system designed
   around decentralized information flow control.
 - [Lost in Translation](./stego/) - A steganographic system that hides information in
   natural language translations.

# <a name="publications"></a> Publications

## Refereed conference and journal publications
 1. Yuhong Zhong, Haoyu Li, Yu Jian Wu, Ioannis Zarkadas, Jeffrey Tao, Evan Mesterhazy, Michael Makris, Junfeng Yang, Amy Tai, Ryan Stutsman, and Asaf Cidon.
    [XRP: In-Kernel Storage Functions with eBPF.](https://www.usenix.org/conference/osdi22/presentation/zhong)
    In *16th USENIX Symposium on Operating Systems Design and Implementation*, OSDI 2022.
    **Jay Lepreau Best Paper Award**.
 1. Chinmay Kulkarni, Badrish Chandramouli, and Ryan Stutsman.
    [Achieving High Throughput and Elasticity in a Larger-than-Memory Store.](https://www.microsoft.com/en-us/research/publication/achieving-high-throughput-and-elasticity-in-a-larger-than-memory-store/)
    In *Proceedings of the VLDB Endowment*, VLDB 2021.
 1. Ankit Bhardwaj, Chinmay Kulkarni, Reto Achermann, Irina Calciu, Sanidhya Kashyap, Ryan Stutsman, Amy Tai and Gerd Zellweger.
    [NrOS: Effective Replication and Sharing in an Operating System.](https://www.usenix.org/conference/osdi21/presentation/bhardwaj)
    In *Proceedings of the 15th USENIX Symposium on Operating Systems Design and Implementation*, OSDI '21.
 1. Joe Novak,  Ryan Stutsman, and Sneha Kumar Kasera.
    Auto-Scaling Cloud-Based Memory-Intensive  Applications.
    In 12th IEEE International Conference on Cloud Computing, IEEE CLOUD 2020.
 1. Ankit Bhardwaj, Chinmay Kulkarni, and Ryan Stutsman.
    [Adaptive Placement for In-memory Storage Functions.](https://www.usenix.org/conference/atc20/presentation/bhardwaj)
    In *Proceedings of the 2020 USENIX Annual Technical Conference*, USENIX ATC '20.
 1. Meysam Taassori, Rajeev Balasubramonian, Siddhartha Chhabra, Alaa Alameldeen, Manjula Peddireddy, Rajat Agarwal, and Ryan Stutsman.
    [Compact Leakage-Free Support for Integrity and Reliability.](http://www.cs.utah.edu/~rajeev/pubs/isca20m.pdf)
    In *Proceedings of the 47th International Symposium onComputer Architecture*, ISCA '20.
 1. Tian Zhang, Dong Xie, Feifei Li, and Ryan Stutsman.
    [Narrowing the Gap Between Serverless and its State with Storage Functions.](http://utah.systems/projects/zhang_shredder)
    In *Proceedings of the ACM Symposium on Cloud Computing*, SoCC'19.
    **Best Paper Runner Up**.
 1. Anirban Nag, C.N. Ramachandra, Rajeev Balasubramonian, Ryan Stutsman, Edouard Giacomin, Hari Kambalasubramanyam, and Pierre-Emmanuel Gaillardon.
    [GenCache: Leveraging In-Cache Operators for Efficient Sequence Alignment.](https://dl.acm.org/doi/10.1145/3352460.3358308)
    In *Proceedings of the 52nd IEEE/ACM International Symposium on Microarchitecture*, MICRO'19.
 1. Tao Zhu, Zhuoyue Zhao, Feifei Li, Weining Qian, Aoying Zhou, Dong Xie, Ryan Stutsman, Haining Li, and Huiqi Hu.
    [SolarDB: Toward a Shared-Everything Database on Distributed Log-Structured Storage.](https://dl.acm.org/citation.cfm?id=3318158)
    In *ACM Transactions on Storage (TOS)*, June 2019.
 1. Gustavo Alonso, Carsten Binnig, Ippokratis Pandis, Kenneth Salem, Jan
    Skrzypczak, Ryan Stutsman, Lasse Thostrup, Tianzheng Wang, Zeke Wang, Tobias
    Ziegler.
    [DPI: The Data Processing Interface for Modern Networks.](http://cidrdb.org/cidr2019/papers/p11-alonso-cidr19.pdf)
    *Conference on Innovative Data Systems Research*, CIDR 2019.
 1. Assaf Eisenman, Asaf Cidon, Evgenya Pergament, Or Haimovich, Ryan Stutsman, Mohammad Alizadeh, and Sachin Katti.
    [Flashield: a Hybrid Key-value Cache that Controls Flash Write Amplification.](https://www.usenix.org/conference/nsdi19/presentation/eisenman)
    In *Proceedings of the 13th USENIX Symposium on Networked Systems Design and Implementation*, NSDI '19.
 1. Joe Novak, Sneha Kumar Kasera, and Ryan Stutsman.
    [Cloud Functions for Fast and Robust Resource Auto-Scaling.](papers/feat.pdf)
    In *11th International Conference on Communication Systems & NetworkS*, COMSNETS 2019.
 1. Chinmay Kulkarni, Sara Moore, Mazhar Naqvi, Tian Zhang, Robert Ricci, and Ryan Stutsman.
    [Splinter: Bare-Metal Extensions for Multi-Tenant Low-Latency Storage.](https://www.usenix.org/node/222600)
    In *Proceedings of the 13th USENIX Symposium on Operating Systems Design and Implementation*, OSDI '18.
 1. Aleksander Maricq, Dmitry Duplyakin, Ivo Jimenez, Carlos Maltzahn, Ryan Stutsman, and Robert Ricci.
    [Taming Performance Variability.](https://www.usenix.org/node/222562)
    In *Proceedings of the 13th USENIX Symposium on Operating Systems Design and Implementation*, OSDI '18.
 1. Junguk Cho, Ryan Stutsman, and Jacobus Van der Merwe.
    [MobileStream: A Scalable, Programmable and Evolvable Mobile Core Control Plane Platform.](https://www.flux.utah.edu/paper/277)
    In *14th International Conference on emerging Networking EXperiments and Technologies*, CoNEXT'18.
 1. Binh Nguyen, Tian Zhang, Bozidar Radunovic, Ryan Stutsman, Thomas Karagiannis, Jakub Kocur, and Jacobus Van der Merwe.
    [ECHO: A Reliable Distributed Cellular Core Network for Hyper-scale Public Clouds.](https://sigmobile.org/mobicom/2018/program.php)
    In *Proceedings of the 24th Annual International Conference on Mobile Computing and Networking*, Mobicom'18.
 1. Yacine Taleb, Ryan Stutsman, Gabriel Antoniu, and Toni Cortes.
    [Tailwind: Fast and Atomic RDMA-based Replication.](https://www.usenix.org/conference/atc18/presentation/taleb)
    In *Proceedings of the 2018 USENIX Annual Technical Conference*, USENIX ATC '18.
 1. Tao Zhu, Zhuoyue Zhao, Feifei Li, Weining Qian, Aoying Zhou, Dong Xie, Ryan Stutsman, Haining Li, and Huiqi Hu.
    [Towards a Shared-Everything Database on Distributed Log-Structured Storage.](https://www.usenix.org/conference/atc18/presentation/zhu)
    In *Proceedings of the 2018 USENIX Annual Technical Conference*, USENIX ATC '18.
 1. Chinmay Kulkarni, Aniraj Kesavan, Tian Zhang, Robert Ricci, and Ryan Stutsman.
    [Rocksteady: Fast Migration for Low-latency In-memory Storage.](https://dl.acm.org/authorize?N47268)
    In *Proceedings of the Twenty-Sixth ACM Symposium on Operating Systems Principles*, SOSP'17.
 1. Asaf Cidon, Daniel Rushton, Stephen M. Rumble, and Ryan Stutsman.
    [Memshare: Memory Resource Sharing in Multi-tenant Web Caches.](http://www.usenix.org/conference/atc17/program/presentation/cidon)
    In *Proceedings of the 2017 USENIX Conference on Annual Technical Conference*, USENIX ATC'17.
 1. Justin Levandoski, David Lomet, Sudipta Sengupta, Ryan Stutsman, Rui Wang.
    [Multi-version Range Concurrency Control in Deuteronomy.](http://www.vldb.org/pvldb/vol8/p2146-levandoski.pdf)
    In *Proceedings of the VLDB Endowment*, VLDB 2016.
 1. John Ousterhout, Arjun Gopalan, Ashish Gupta, Ankita Kejriwal, Collin Lee,
    Behnam Montazeri, Diego Ongaro, Seo Jin Park, Henry Qin, Mendel Rosenblum,
    Stephen Rumble, Ryan Stutsman, Stephen Yang
    [The RAMCloud Storage System.](http://dl.acm.org/ft_gateway.cfm?id=2806887&type=pdf)
    In *ACM Transactions on Computer Systems*, TOCS 2015.
 1. Darko Makreshanski, Justin Levandoski, Ryan Stutsman.
    [To Lock, Swap, or Elide: On the Interplay of Hardware Transactional Memory and Lock-Free Indexing.](http://www.vldb.org/pvldb/vol8/p1298-makreshanski.pdf)
    In *Proceedings of the VLDB Endowment*, VLDB 2015.
 1. Ryan Stutsman, Collin Lee, and John Ousterhout.
    [Experience with Rules-Based Programming for Distributed, Concurrent, Fault-Tolerant Code.](https://www.usenix.org/system/files/conference/atc15/atc15-paper-stutsman.pdf)
    In *Proceedings of the 2015 USENIX Conference on Annual Technical Conference*,
    USENIX ATC'15, pages 17-30, Santa Clara, CA, USA, 2015. USENIX Association.
 1. Justin Levandoski, David Lomet, Sudipta Sengupta, Ryan Stutsman, Rui Wang.
    [High Performance Transactions in Deuteronomy.](http://www.cidrdb.org/cidr2015/Papers/CIDR15_Paper15.pdf)
    *Conference on Innovative Data Systems Research*, CIDR 2015.
 1. Asaf Cidon, Stephen M. Rumble, Ryan Stutsman, Sachin Katti, John
    Ousterhout, and Mendel Rosenblum.
    [Copysets: Reducing the Frequency of Data Loss in Cloud Storage.](http://www.stanford.edu/~cidon/materials/CR.pdf)
    In *Proceedings of the 2013 USENIX Conference on Annual Technical Conference*,
    USENIX ATC'13, pages 37­48, Berkeley, CA, USA, 2013. USENIX Association.
    (**Best Student Paper Award**)
 1. Diego Ongaro, Stephen M. Rumble, Ryan Stutsman, John Ousterhout, and Mendel Rosenblum.
    [Fast Crash Recovery in RAMCloud.](http://www.stanford.edu/~ouster/cgi-bin/papers/ramcloud-recovery.pdf)
    In *Proceedings of the Twenty-Third ACM Symposium on Operating Systems Principles*,
    SOSP '11, pages 29-41, New York, NY, USA, 2011. ACM.
 1. John Ousterhout, Parag Agrawal, David Erickson, Christos Kozyrakis, Jacob Leverich,
    David Mazi&egrave;res, Subhasish Mitra, Aravind Narayanan, Diego Ongaro, Guru Parulkar,
    Mendel Rosenblum, Stephen M. Rumble, Eric Stratmann, and Ryan Stutsman.
    [The Case for RAMCloud.]("http://cacm.acm.org/magazines/2011/7/109885-the-case-for-ramcloud/fulltext)
    *Communications of the ACM*,
    54(7):121-130, July 2011.
 1. Arjun Roy, Stephen M. Rumble, Ryan Stutsman, Philip Levis, David Mazi&egrave;res,
    and Nickolai Zeldovich.
    [Energy Management in Mobile Devices with the Cinder Operating System.](http://www.scs.stanford.edu/~rumble/papers/eurosys2011-roy.pdf)
    In *Proceedings of the Sixth conference on Computer Systems*,
     EuroSys '11, pages 139-152, New York, NY, USA, 2011. ACM.
 1. Christian Grothoff, Krista Grothoff, Ryan Stutsman, Ludmila Alkhutova, and Mikhail J. Atallah.
    [Translation-based Steganography.]("http://iospress.metapress.com/content/j97333w402k26404/")
    *Journal of Computer Security*, 17(3):269-303, 2009.
 1. Ryan Stutsman, Mikhail Atallah, Christian Grothoff, and Krista Grothoff.
    [Lost in Just the Translation.](papers/lijtt.pdf)
    In *Proceedings of the 2006 ACM Symposium on Applied Computing*,
    pages 338-345. ACM, April 2006.

## Refereed workshop publications
 1.  Ankit Bhardwaj, Todd Thornley, Vinita Pawar, Reto Achermann, Gerd Zellweger, and Ryan Stutsman.
     Cache-coherent Accelerators for Persistent Memory Crash-consistency.
     In *Proceedings of the 14th ACM Workshop on Hot Topics in Storage and File Systems*, HotStorage '22.
     **Intel Best Paper Award**
 1. Yuhong Zhong, Hongyi Wang, Yu Jian Wu, Asaf Cidon, Ryan Stutsman, Amy Tai, and Junfeng Yang.
    [BPF for storage: an exokernel-inspired approach.](https://sigops.org/s/conferences/hotos/2021/papers/hotos21-s07-zhong.pdf)
    Workshop on Hot Topics in Operating Systems HotOS' 21.
 1. Ankit Bhardwaj, Meghana Gupta, and Ryan Stutsman.
    [On the Impact of Isolation Costs on Locality-aware Cloud Scheduling.](https://www.usenix.org/conference/hotcloud20/presentation/bhardwaj)
    In *12th USENIX Workshop on Hot Topics in Cloud Computing*, HotCloud '20.
 1. Jared Plumb, Sneha Kasera, and Ryan Stutsman.
    Hybrid Network Clusters Using Common Gameplay for Massively Multiplayer Online Games.
    In *Foundations of Digital Games*, FDG '18, 2018.
 1. Jared Plumb and Ryan Stutsman.
    Exploiting Google’s Edge Network for Massively Multiplayer Online Games.
    In *IEEE 2nd International Conference on Fog and Edge Computing*, ICFEC '18, 2018.
 1. Tian Zhang and Ryan Stutsman.
    JavaScript for Extending Low-latency In-memory Key-value Stores.
    In *Proceedings of the 9th USENIX Conference on Hot Topics in Cloud Computing*, HotCloud’17.
 1. Aniraj Kesavan, Robert Ricci, and Ryan Stutsman.
    [To Copy or Not to Copy: Making In-Memory Databases Fast on Modern NICs.](papers/copy-not-to-copy.pdf)
    In *4th Workshop on In-memory Data Management*, IMDM'16.
 1. Mohammed Al-Mahfoudh, Ganesh Gopalakrishnan, and Ryan Stutsman.
    [Toward Bringing Distributed Systems Design Upon Rigorous Footing.](http://ieeexplore.ieee.org/document/7785746/)
    In *IEEE Workshop on Formal Methods and Integration*, FMi'16.
 1. Mohammed Al-Mahfoudh, Ganesh Gopalakrishnan, Ryan Stutsman.
    [Toward Rigorous Design of Domain-specific Distributed Systems.](http://formalverification.cs.utah.edu/ds2/papers/formalise2016.pdf)
    In *Proceedings of the 4th FME Workshop on Formal Methods in Software Engineering*,
    FormaliSE'16, Austin, TX, USA, 2016.
 1. Ryan Stutsman and John Ousterhout.
    [Toward Common Patterns for Distributed, Concurrent, Fault-Tolerant Code.](papers/stutsman-dcft-hotos13.pdf)
    In *Proceedings of the 13th USENIX Conference on Hot Topics in Operating Systems*,
    HotOS'13, Berkeley, CA, USA, 2013. USENIX Association.
 1. Stephen M. Rumble, Diego Ongaro, Ryan Stutsman, Mendel Rosenblum, and John K. Ousterhout.
    [It's Time for Low Latency.](http://www.scs.stanford.edu/~rumble/papers/latency_hotos11.pdf)
    In *Proceedings of the 13th USENIX Conference on Hot Topics in Operating Systems*,
    HotOS '11, pages 11-15, Berkeley, CA, USA, 2011. USENIX Association.
 1. Stephen M. Rumble, Ryan Stutsman, Philip Levis, David Mazi&egrave;res, and Nickolai Zeldovich.
    [Apprehending Joule Thieves with Cinder.](papers/mobiheld04-rumble.pdf)
    In *MobiHeld '09: Proceedings of the 1st ACM workshop on Networking,
    systems, and applications for mobile handhelds*, pages 49-54, 2009.
 1.  Jad Naous, Ryan Stutsman, David Mazi&egrave;res, Nick McKeown, and Nickolai Zeldovich.
     [Delegating Network Security with More Information.](papers/wren27-naous.pdf)
     In *Proceedings of the 1st ACM Workshop on Research on Enterprise Networking*,
     WREN '09, pages 19-26, 2009.
 1.  Christian Grothoff, Krista Grothoff, Ludmila Alkhutova, Ryan Stutsman, and Mikhail Atallah.
     [Translation-Based Steganography](papers/lit.pdf)
     In *Proceedings of Information Hiding Workshop*,
     IH 2005, pages 213-233. Springer-Verlag, 2005.

## Unrefereed publications
 1. Chinmay Kulkarni, Aniraj Kesavan, Robert Ricci, and Ryan Stutsman.
    [Beyond Simple Request Processing with RAMCloud.](http://sites.computer.org/debull/A17mar/p62.pdf)
    IEEE Data Engineering Bulletin, March 2017.
 1. Justin Levandoski, Sudipta Sengupta, Ryan Stutsman, and Rui Wang.
    [Transaction Processing Techniques for Modern Hardware and the Cloud.](http://sites.computer.org/debull/A15mar/p50.pdf)
    IEEE Data Engineering Bulletin, March 2015.
 1. Stephen M. Rumble, Ryan Stutsman, Philip Levis, David Mazi&egrave;res, and Nickolai Zeldovich.
    [Apprehending Joule Thieves with Cinder.]("papers/rumble-cinder-ccr.pdf")
    *SIGCOMM Computer Communication Review*, 40(1):106-111, 2010.
 1. John Ousterhout, Parag Agrawal, David Erickson, Christos Kozyrakis, Jacob Leverich,
    David Mazi&egrave;res, Subhasish Mitra, Aravind Narayanan, Guru Parulkar, Mendel Rosenblum,
    Stephen M. Rumble, Eric Stratmann, and Ryan Stutsman.
    [The Case for RAMClouds: Scalable High-Performance Storage Entirely in DRAM.](http://doi.acm.org/10.1145/1713254.1713276)
    *SIGOPS Operating Systems Review*, 43(4):92-105, December 2009.

<!-- The missing one is the RAMCloud TR. But it is irrelevant given SIGOPS version. -->
<!--
 1.  Christian Grothoff, Krista Grothoff, Ludmila Alkhutova, Ryan Stutsman, and Mikhail Atallah.
     [Translation-Based Steganography.](https://www.cerias.purdue.edu/assets/pdf/bibtex_archive/2005-39.pdf)
      Technical Report CSD TR 05-009, Purdue University, 2005.
 1.  Arjun Roy, Stephen M. Rumble, Ryan Stutsman, Philip Levis, David Mazi&egrave;res,
     and Nickolai Zeldovich.
     [Energy Management in Mobile Devices with the Cinder Operating System.](http://hci.stanford.edu/cstr/reports/2010-02.pdf)
     Technical Report CSTR-2010-02, Stanford University, June 2010.
-->

## Dissertation

[Durability and Crash Recovery in Distributed In-Memory Storage Systems.](./papers/thesis.pdf)
PhD thesis, Stanford University, Stanford, CA, USA, December 2013.


<!--
# <a name="talks"></a> Talks

 1. Bare-Metal Extensions for Multi-Tenant Low-Latency Storage.
    Invited Talk, INRIA Rennes, 2018.
 1. Massive Main Memory for the Masses.
    Invited Talk, EPFL, 2018.
 1. [Multi-version Range Concurrency Control in Deuteronomy.](http://www.vldb.org/pvldb/vol8/p2146-levandoski.pdf)
    VLDB 2016.
 1. [Experience with Rules-Based Programming for Distributed, Concurrent, Fault-Tolerant Code.](https://www.usenix.org/system/files/conference/atc15/atc15-paper-stutsman.pdf)
    USENIX ATC'15.
 1. [High Performance Transactions in Deuteronomy.](http://www.cidrdb.org/cidr2015/Papers/CIDR15_Paper15.pdf)
    CIDR 2015.
 1. [Toward Common Patterns for Distributed, Concurrent, Fault-Tolerant Code.](papers/stutsman-dcft-hotos13.pdf)
    HotOS'13.
 1. [Fast Crash Recovery in RAMCloud.](http://www.stanford.edu/~ouster/cgi-bin/papers/ramcloud-recovery.pdf)
    SOSP '11.
 1. [Energy Management in Mobile Devices with the Cinder Operating System.](http://www.scs.stanford.edu/~rumble/papers/eurosys2011-roy.pdf)
    EuroSys '11.
 1. [Lost in Just the Translation.](papers/lijtt.pdf)
    ACM SAC '06.
-->

# <a name="activities"></a> Activities

<!--
- Outreach
  - FIRST Lego League Junior, Assistant Team Coach 2018-present.
  - Oregon-Davis Junior/Senior High School; Invited STEM Career Speaker;
       Hamlet, Indiana; 2015.
  - University of Utah IT Professionals Meeting Invited Talk, "An Overview of
   Recent Speculative Execution Vulnerabilities", June 2019.

- Department Service
  - School of Computing Database Faculty Search Committee, 2017;
  - University of Utah School of Computing Outstanding Teaching/TA Awards Selection Committee,
AY ’17-’18;
  - School of Computing Ph.D. Admissions Committee, 2014, 2015, 2016, 2018, 2020.
  - College of Engineering Engineering Day Session Organizer, “Undergraduate Research in Computer Science”, 2020;
  - School of Computing Mock Panel Participant, 2019, 2020;
  - School of Computing Undergraduate Research Liaison, 2019-present;
  - School of Computing Graduate Admit Visit Day Coordinator, 2017, 2018;
  - School of Computing Undergraduate Advisory Committee (UGSAC) Faculty Advisor, 2015-present.
- College Service
  - College of Engineering Scholarship Committee, 2019, 2020;
  - College of Engineering Orientation Panel, 2019 (3×), 2020.
- University Service
  - Office of Undergraduate Research Undergraduate Research Symposium Poster Judge, 2019 (2×).
-->

- Conference Organization
  - ACM SoCC '21 Publications Chair
  - HotCloud ’20 Program Co-chair, 22 paper program selected from 95 submissions;
  - OSDI’20 Artifact Evaluation Committee Co-chair, 53 artifact submissions;
  - NSDI ’19 Poster Co-chair, 48 posters;
- Program Committees
  - SOSP '19, '21, '23;
  - OSDI '18, '20 (Heavy Member), '23;
  - VLDB '17 (Industrial Track), '23;
  - ACM SYSTOR '21 (Distinguished Reviewer);
  - USENIX ATC '19, '21;
  - NSDI '19, '21;
  - HotCloud '19 (Workshop);
  - ICDCS '18;
  - EDBT '18;
  - ICDE '18;
  - SIGMOD '17, '18, (Distinguished Program Committee Member both times);
  - SIGMOD '16 Demo Committee;
  - ICDE ’16;
  - IMDM ’14, ’15, ’16 (Workshop);
  - SIGMETRICS ’15.
- NSF Panelist 2017, 2018, 2019x2, 2022.

<!--
- Journal Reviewing
  - ACM Transactions on Storage (TOS);
  - IEEE Transactions on Cloud Computing (TOCC);
  - ACM SIGMOD Transactions on Database Systems (TODS);
  - IEEE Transactions on Knowledge and Data Engineering (TKDE);
  - ACM SIGOPS Transactions on Computer Systems (TOCS).
-->


