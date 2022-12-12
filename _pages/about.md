---
permalink: /
title: "Welcome to SSLab!"
excerpt: "About SSLab"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

SSLab(Secure Systems Lab) is a research laboratory under the Department of Computer Science & Information Engineering at National Taiwan University. Our research involve in operating systems, virtualization, computer security, and computer architecture. It is directed by [Prof. Shih-Wei Li](https://www.csie.ntu.edu.tw/people/bio.php?PID=46738).

We are always looking for highly-motivated undergraduate and graduate (MS and PhD) students. Please contact us if you are interested in working with us.




Main Research
======

Confidential Computing
------
Modern computer systems rely on large, monolithic, and privileged systems software such as the OS kernel or hypervisor to manage hardware resources for applications and virtual machines (VMs). These systems software has become increasingly complex to satisfy the growing demand for functionality and performance. The safety of the user’s computation and data depends on the trustworthiness of the potentially buggy OS kernel and hypervisor codebase. Attackers who successfully exploit these software vulnerabilities can gain unfettered access to user data.

Recently, various software and hardware approaches have been proposed to protect user data from privileged attackers. I was the lead developer of SeKVM, a secure Linux/KVM hypervisor that relies on a formally verified core to safeguard the confidentiality and integrity of VM data against the untrusted host Linux kernel.

Software and OS/Hypervisor Security
------
I am interested in developing efficient and scalable technology to secure core software systems, including the OS kernel and hypervisor, for supporting applications, containers, and virtual machines deployed to the cloud, mobile, and automotive systems. Areas of interest include software and hardware-based hardening, fault-tolerant computing, and static/dynamic software analysis, fuzzing, and formal verification.

Linux/KVM for Arm
------
In the past, I used to work closely with the open source community for KVM/Arm. The benchmarks I built for measuring KVM performance have been merged into the mainline kvm-unit-test benchmark suite. I also contributed to developing nested virtualization support for Arm and optimizing KVM’s performance for Arm hardware with [VHE](https://developer.arm.com/documentation/102142/0100/Virtualization-Host-Extensions).
