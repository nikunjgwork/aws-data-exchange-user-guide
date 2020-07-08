# Resilience in AWS Data Exchange<a name="disaster-recovery-resiliency"></a>

The AWS global infrastructure is built around AWS Regions and Availability Zones\. AWS Regions provide multiple physically separated and isolated Availability Zones, which are connected with low\-latency, high\-throughput, and highly redundant networking\. With Availability Zones, you can design and operate applications and databases that fail over between Availability Zones without interruption\. Availability Zones are more highly available, fault tolerant, and scalable than traditional single or multiple data center infrastructures\.

AWS Data Exchange has a single, globally available product catalog offered by providers\. Subscribers can see the same catalog, regardless of which region they are using\. The resources underlying the product \(data sets, revisions, assets\) are regional resources that you manage programmatically or through the AWS Data Exchange console in supported AWS Regions\. AWS Data Exchange replicates your data across multiple Availability Zones within the AWS Regions where the service operates\. For information about supported regions, see [Global Infrastructure Region Table](http://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/)\.

For more information about AWS Regions and Availability Zones, see [AWS Global Infrastructure](https://aws.amazon.com/about-aws/global-infrastructure/)\.