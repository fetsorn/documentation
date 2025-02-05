---
title: "TrueNAS CORE and Enterprise"
geekdocCollapseSection: true
weight: 10
---

![TNOpenStorageLogo](/images/tn-openstorage-logo.png)

TrueNAS is the world’s most popular Open Source storage operating system and is the most efficient solution for managing and sharing data over a network.
It is the simplest way to create a safe, secure, centralized, and easily accessible place for your data.
TrueNAS Open Storage provides unified storage for file, block, object, and application data.

TrueNAS can be installed on virtually any hardware platform and is suitable for home, business, and enterprise applications.
There are three editions of TrueNAS that enable a broad range of applications while sharing common management tools and enabling data transfers:

{{< columns >}}
![TNCORELogo](/images/tn-core-logo.png)

**TrueNAS CORE** is free and Open Source and is the successor to the wildly popular FreeNAS.
It runs on virtually any x86_64 system and provides a broad set of features for many users.
Plugin applications like Plex, NextCloud, and Asigra allow the functionality of a system to be customized for many use cases.
<--->
![TNEnterpriseLogo](/images/tn-enterprise-logo.png)

**TrueNAS Enterprise** is provided as a system with either single or dual controllers to enable High Availability (HA).
It can also be provided with Enterprise-grade support from iXsystems.
Coupled with the TrueNAS M-Series system, it scales to 15GB/s and 20 PB with five 9’s of uptime.
<--->
![TNSCALELogo](/images/tn-scale-logo.png)

**TrueNAS SCALE** is the latest member of the TrueNAS family and provides Open Source HyperConverged Infrastructure including Linux containers and VMs.
TrueNAS SCALE includes the ability to cluster systems and provide scale-out storage with capacities of up to hundreds of Petabytes.
It is currently in development and will be available for deployment in 2021.
{{< /columns >}}

TrueNAS Software products offer market-leading features to be the most effective NAS solution:

{{< tabs "TrueNAS Features" >}}
{{< tab "OpenZFS" >}}
## OpenZFS for Maximum Protection and Performance

All TrueNAS editions leverage the enterprise-grade OpenZFS file system to provide an all-inclusive data management solution that is designed for decades of continuous use.
To provide the perfect balance between total storage capacity and data redundancy, storage pools can be configured in a variety of RAIDZ or Mirrored configurations.
Pools can even be expanded when new disks or SSDs are added to the system, allowing your storage environment to grow with application requirements. 

ZFS protects your data with features like Copy-on-Write, Checksums, Scrubbing, and 2-Copy Metadata.
Automated replication ensures you can keep a bit-for-bit identical copy of your data safe in a remote storage location and fast resilvering times mean that if a disk fails, a replacement disk can be quickly integrated into the degraded data storage pool.
ZFS uses efficient snapshot and cloning techniques to maximize available space, as well as in-line data compression, thin provisioning, and deduplication.
{{< /tab >}}
{{< tab "Security Focus" >}}
## Security-focused to give you Peace of Mind

TrueNAS supports a variety of security solutions including self-encrypted drives (SEDs) and ZFS native dataset encryption.
Access control lists are fully customizable and provide another layer of protection for sensitive data.
TrueNAS supports FIPS 140-2 Level 2 drives and installs with secure defaults in place, including encryption for file transfers and disabling SSH.
Local users and groups can be managed, along with integrating TrueNAS with LDAP, Active Directory, Kerberos, and NIS.
For enterprises, centralized key management (KMIP) is also available.
{{< /tab >}}
{{< tab "Easy Data Sharing" >}}
## Sharing Your Data has Never Been Easier

TrueNAS supports all the prominent network file sharing and remote backup options, and can even be expanded with applications from FreeBSD or Linux.
Supported sharing protocols include NFS (v3,4), SMB (v1,2,3,4), AFP, FTP, WebDAV, and rsync.
TrueNAS fully supports block sharing (iSCSI, Fibre Channel) and has been certified for use with vSphere, Citrix, and Veeam.
Want to securely import or back up data with a Cloud Storage Provider?
No problem!
TrueNAS can even store and sync your S3 data with an automated schedule.
{{< /tab >}}
{{< tab "Additional Features" >}}
## TrueNAS Delivers a Rich Set of Features

There are an enormous number of features in each TrueNAS edition.
You can read the Open Source software, try out TrueNAS in a VM at zero cost, or have a look through this chart which summarizes the key features (TrueNAS 12.0 features are in blue).

![TrueNASFeatures](/images/CORE/Features.png)

TrueNAS SCALE uses much of the same TrueNAS CORE source code, but adds a few different capabilities which are defined by this acronym:

**S**cale-out ZFS<br>
**C**onverged<br>
**A**ctive-active<br>
**L**inux containers<br>
**E**asy-to-manage<br>

{{< /tab >}}
{{< tab "Flexible Hardware" >}}
## Run TrueNAS on Any System

TrueNAS delivers Software Defined Storage (SDS) and runs on any x86_64 server, no matter how old or modern.
Intel and AMD processors or any generation are supported, whether it’s a single core or a sixty-four core behemoth.
The TrueNAS [hardware guide]({{< relref "COREHardwareGuide.md" >}}) provides recommendations to assist you in building your own systems.

TrueNAS software has been developed under the sponsorship of iXsystems since 2009 and uses a large team of professionals who develop, build, QA, document, and support the Open Source software and the TrueNAS community.
Since the TrueNAS software is free, iXsystems grows its business by building professional and enterprise-grade systems that have similar reliability to the major NAS vendors, but at a much lower Total Cost of Ownership (TCO).
The iXsystems proposition is that TrueNAS enables dramatic storage cost savings through Open Source economics.
TrueNAS provides the industry’s most powerful Open Storage.

TrueNAS can be downloaded from [this page](https://www.truenas.com/download-tn-core/).

The current TrueNAS systems available cover a wide range of sizes and use cases!
Go to the [hardware]({{< relref "/Hardware/_index.md" >}}) section to learn more about each family of TrueNAS hardware.
{{< /tab >}}
{{< /tabs >}}

## Join the Expert Community

TrueNAS comprises both the Open Source software and an experienced and expert community developed over the last dozen years.
Ask for advice and contribute your experiences for others to use.
The [community](https://www.truenas.com/community/) can save you many hours and be a great resource for new projects and applications.
If you need more professional support, iXsystems offers Bronze/Silver/Gold Enterprise support including 24x365 coverage and onsite support with its systems.

## TrueCommand Manages your NAS Fleet

TrueCommand is a single Pane-of-Glass management application that takes the repetitive work out of multi-TrueNAS management by centralizing system alerts, reports, and analytics in one easy to use interface. It supports users and teams with 24x365 global operations, role-based access control, and a full log of every TrueNAS configuration change.
TrueCommand runs on docker, VMs, or as a cloud service and is free to users with less than 50 drives and affordable for those with larger installations.
Read more information about TrueCommand in the [overview]({{< relref "/TrueCommand/_index.md" >}}) article.

![TrueCommandOverview](/images/TrueCommand/Overview.png)
