##Intel DCPMM public informations 
##
In this document you will find an overview of all public information related to Intel DCPMM, the Intel non volatile DIMM memory module which use 3DXPoint.

What will you find are:

       * DCPMM intro
       * Software developper content
       * OS/VMM/Middleware information
       * Compatible application list###
Everything start here:

##[DCPMM intro]

**Intel DCPMM Public web site**
{https://software.intel.com/en-us/persistent-memory}

**Intro to DCPMM**
{https://software.intel.com/en-us/blogs/2018/10/30/new-software-development-opportunities-with-big-affordable-persistent-memory#}

**Persistant memory Wiki**
{https://nvdimm.wiki.kernel.org/}

**DCPMM pictures**
{https://newsroom.intel.com/editorials/re-architecting-data-center-memory-storage-hierarchy/}

##[Software developper content]

**PMEM.IO website**
{http://pmem.io/}

**PMDK GitHub**
{https://github.com/pmem/pmdk/}

**Recommanded method to profile your application and check if you can take advantage of DCPMM using VTune™ Amplifier Platform Profiler**
{https://software.intel.com/en-us/articles/vtune-amplifier-platform-profiler}

**Emulate Persistent memory using DRAM with Linux (need to support DAX)**
{https://software.intel.com/en-us/articles/how-to-emulate-persistent-memory-on-an-intel-architecture-server} 

**Build your application (Windows or Linux) which take advantage of persistant memory**
{https://software.intel.com/en-us/persistent-memory/get-started}

    C++ (libpmemobj library)
{http://pmem.io/pmdk/libpmemobj/}

**Langague support, testing compatibility, debug...**
{https://software.intel.com/en-us/persistent-memory/get-started}

**Google group on PMEM**
{https://groups.google.com/forum/#}!forum/pmem

**Benchmark persistant memory using PMDK and FIO Workloads**
{https://www.youtube.com/watch?v=vs1MpsHiNnA}
{http://pmem.io/2018/06/25/fio-tutorial.html} (FIO tuto)
{https://github.com/axboe/fio} (FIO GitHub)
{https://github.com/axboe/fio/tree/master/examples} (FIO config files which include pmemblck)


**NDCTL Users Guide and documentation**
**Linux utility to manage the Linux LIBNVDIMM Kernel subsystem and designed to work with various non-volatile memory devices (NVDIMMs) from different vendors.**
{https://docs.pmem.io/ndctl-users-guide}
{https://pmem.io/ndctl/}

##[OS/VMM/Middleware information]
**Windows Server 2016**
{https://channel9.msdn.com/Events/Build/2016/P470}

**Suse: Persistant memory implementation**
{https://www.suse.com/c/nvdimm-enabling-suse-linux-enterprise-12-service-pack-2/}

**Red Hat***

**SUSE***

**Canonical***

**VMware***
Testing Github here.
Another try here.

**KVM**

**Xen***

**Java (in Oracle)**


##[Compatible application list]
**SQL'16 **
{https://channel9.msdn.com/Shows/Data-Exposed/SQL-Server-2016-and-Windows-Server-2016-SCM--FAST}

**Oracle Exadata \& TimesTen**
{https://blogs.oracle.com/exadata/persistent-memory-accelerator} 

**Spark SQL (video)**
{https://www.intel.com/content/www/us/en/products/docs/memory-storage/optane-persistent-memory/accelerate-ai-demo-video.html}

**Intel® Optane™ DC Persistent Memory \& SAP HANA***
{https://www.intel.com/content/www/us/en/big-data/partners/sap/persistent-memory-brief.html}
{https://cloud.google.com/blog/topics/partners/available-first-on-google-cloud-intel-optane-dc-persistent-memory}

**RocksDB***

**Redis***
{https://www.snia.org/sites/default/files/SDC/2018/presentations/PM/Shu\_Kevin\_Optimize\_Redis\_with\_NextGen\_NVM.pdf}
What is Pmem-Redis?
{https://github.com/pmem/pmem-redis}

**Apache* Cassandra**


**Cloudera**


**Optane DC DIMMs \& OpenStack: App Direct Mode**
{underlinehttps://review.openstack.org/#/c/601596/5/specs/stein/approved/virtual-persistent-memory.rstunderline}


**Optane DC DIMMs \& K8s: App Direct Mode**
{https://github.com/kubernetes/enhancements/issues/178}
{https://github.com/intel/pmem-csi}
