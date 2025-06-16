+++
title = "This Month in Fedora (June 2025)"
url = "/en/posts/this-month-in-fedora-2025-06"
date = 2025-06-13T20:58:49-03:00
description = "Update on what I did in the Fedora Project in June 2025."
tags = ["fedora"]
draft = true
+++

## Election Results

On June 3rd, the [election results][f42-elections] for the Fedora Project were announced. I was happy to see that all of my favorite candidates were elected. Here are the results:

+ **Council**: Miro Hrončok and Aleksandra Fedorova
+ **FESCo**: Neal Gompa, Stephen Gallagher, Fabio Valentini, and Michel Lind
+ **Mindshare Committee**: Emma Kidney, Sumantro Mukherjee, Akashdeep Dhar, and Luis Bazan
+ **EPEL Steering Committee**: Davide Cavalca, Robbie Callicotte, and Neal Gompa

## Package Maintenance

Just maintenance of the [bfs][bfs-src] package.

### New Packages

A [user asked][bfs-epel10-request] if I could also maintain bfs for EPEL 10.

| Package        | Version | Release                |
|----------------|---------|------------------------|
| [bfs][bfs-src] | 4.0.6   | [1.el10_1][bfs-epel10] |

### Updates

| Package        | Version | Release                                |
|----------------|---------|----------------------------------------|
| [bfs][bfs-src] | 4.0.7   | [1.fc43][bfs-fc43], [1.fc42][bfs-fc42] |

[f42-elections]: https://communityblog.fedoraproject.org/f42-elections-results/
[bfs-src]: https://src.fedoraproject.org/rpms/bfs
[bfs-epel10-request]: https://bugzilla.redhat.com/show_bug.cgi?id=2371050
[bfs-epel10]: https://bodhi.fedoraproject.org/updates/FEDORA-EPEL-2025-7e71075e97
[bfs-fc43]: https://bodhi.fedoraproject.org/updates/FEDORA-2025-a9d3b24d09
[bfs-fc42]: https://bodhi.fedoraproject.org/updates/FEDORA-2025-3abca4b043
