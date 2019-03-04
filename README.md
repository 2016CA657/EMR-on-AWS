# EMR-on-AWS

You can set up a (single node would suffice in the context of this course) Hadoop Cluster on AWS to run EMR, and yet be in the free tier.
There are a few things to consider, including the type of instances you are running (only micro instances allowed in the free tier for EC), the number on nodes and the GB used.

All the excercises and assignments in this course do not require you to go over  the limit.

If you are anxious about that, you can consider alternative hosted MR solutions like Google DataProc, but you do not have to.
In order to help you see it is possible to use AWS and to give you some pointers on how to approach it, please see links below.
Note that most of them consider 4 nodes cluster. This is beyond what you are requested to do, and with 1 node cluster you can certainly and more likely stay within the free tier.
Do not forget that you have also a limited amount of hours per months in your free tier, so DO NOT leave your instances running.


Useful resources to set up EMR on AWS remaining on the free tier:
* https://stackoverflow.com/questions/33836518/hadoop-in-the-aws-free-tier
* https://blog.gaelfoppolo.com/lets-try-hadoop-on-aws-13a23e641490 
* https://www.edureka.co/blog/install-apache-hadoop-cluster/
* https://blog.insightdatascience.com/spinning-up-a-free-hadoop-cluster-step-by-step-c406d56bae42

