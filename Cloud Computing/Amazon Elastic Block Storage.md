# What is EBS?
Amazon Elastic Block Store (AWS EBS) is a raw block-level storage service designed to be used with Amazon EC2 instances. When mounted to Amazon EC2 instances, Amazon EBS volumes can be used like any other raw block device: they can be formatted with a specific file system, host operating systems, and applications, and have snapshots or clones made from them.

This means that the data is kept on the AWS EBS servers even when the EC2 instances are shut down. The data volumes can be dynamically attached, detached, and scaled with any EC2 instance, just like a physical block storage drive. As a highly dependable cloud service, the EBS offering guarantees 99.999% availability.

# Types of EBS
## There are two Amazon EBS volume type categories:
SSD-backed volumes 
HDD-backed volumes

## The SSD-backed volumes provided by Amazon EBS fall into these categories:
### General Purpose SSD — Provides a balance of price and performance. We recommend these volumes for most workloads.

### Provisioned IOPS SSD — Provides high performance for mission-critical, low-latency, or high-throughput workloads.

### The HDD-backed volumes provided by Amazon EBS fall into these categories:
Throughput Optimized HDD — A low-cost HDD designed for frequently accessed, throughput-intensive workloads.

Cold HDD — The lowest-cost HDD design for less frequently accessed workloads.

# What Is AWS EFS?
AWS Elastic File System (EFS) is one of the three main storage services offered by Amazon. It is a scalable, cloud-based file system for Linux-based applications and workloads that can be used in combination with AWS cloud services and on-premise resources.

EFS offers a choice between two storage classes, Infrequent Access, and Standard access, depending on your needs.

Standard access storage is designed for frequently accessed files.
Infrequent Access is intended for storing long-lived but less used files at a lower cost.
