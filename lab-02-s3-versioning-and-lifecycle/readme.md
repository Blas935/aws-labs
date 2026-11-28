**Lab 02 - S3 Versioning and Lifecycle**

## Overview

The objective of this lab was to learn how to preserve different versions of an object, recover accidentally deleted files, and configure lifecycle rules to manage old versions automatically.

**Services Used**

-Amazon S3

**My Lab Environment**

- AWS Academy Cloud Foundations Sandbox
- AWS Management Console

 **What is going to be learned**

- How to enable and manage S3 bucket versioning.
- How AWS stores multiple versions of the same object.
- The difference between creating a delete marker and permanently deleting an object.
- How to recover accidentally deleted files.
- How to configure lifecycle rules to automatically delete old object versions.



Versioning provides an additional layer of protection against accidental deletions and unwanted modifications. Lifecycle rules help balance data retention and storage costs by automatically removing old versions after a defined period.

**Conclusion**

Thanks to this lab, I gained a better understanding of how object versioning works in AWS. I found the difference between creating a delete marker and permanently deleting an object particularly interesting.

These features can be especially useful when updating files, as previous versions can be preserved in case something goes wrong. Lifecycle rules also allow us to define a retention period before old versions are automatically deleted, helping prevent unnecessary storage usage while maintaining recovery capabilities.

**Status**

Completed