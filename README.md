Comparing-of-single-machine
===
I analyzed and compared the frameworks of three single machine graph computing frameworks, GraphChi, X-Stream and GridGraph.
I will introduce the environment of my machine, my principle for chosen the datasets and their source, and the guide to install
these frameworks in my machine.

Environment of my machine
-----
Experiments are conducted on CloudLab Wisconsin server, which has two Intel E5-2660 v3 10-core CPUs at 2.60 GHz(Haswell EP), 160GB ECC Memory. Because we need to test how the performance difference between HDD and SSD, so we select two types of disks. An intel DC S3500 480 GB 6G SATA SSDs and two 1.2TB 10K RPM 6G SAS SFF HDDs. Because of some framework has optimization for disk, so we special select the server that has both SSD and HDD.

Principle of datasets
----
All data sets are measured by the number of vertices, increasing ten folds at a time. So that it can measures all in-memory and out-of-memory conditions.
source: http://an.kaist.ac.kr/traces/WWW2010.html, http://snap.stanford.edu/index.html
