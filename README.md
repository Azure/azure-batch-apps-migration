# Azure Batch Apps Migration

[Azure Batch](https://azure.microsoft.com/services/batch) is a fully-managed cloud service that enables you to run
large-scale parallel and high performance computing (HPC) applications
efficiently on Azure. With Batch, you can schedule compute-intensive
work to run on a managed collection of virtual machines, and have Batch
automatically scale compute resources to meet the needs of your jobs.

When Batch first became available on Azure, a number of additional
capabilities like application packages, job splitter, and task processor
were made available as part of a preview service named Batch Apps. The
Batch Apps preview functionality is now available in Batch, so **the
preview of Batch Apps will be discontinued on September 30, 2016**.
To avoid downtime, workloads that use the Batch Apps preview need
to be migrated to Batch by using the updated Batch API.

This repository contains documentation that can help you with the migration
of your Batch Apps workloads to Batch. The following items are included:

* [Developer Migration Guide](developer-migration-guide.pdf): A step-by-step guide that can guide you through the process of migrating your Batch Apps workloads to Batch.
* [Job Manager and Task Processor Templates for Azure Batch User Guide](azure-batch-templates-user-guide.pdf): A reference guide about two new Visual Studio templates that can help you to move your Batch Apps code to Batch with the least amount of effort.

If you need additional information or advice when migrating your Batch Apps
solution to Batch, or if you are having trouble diagnosing or fixing a
problem with your ported code, don't hesitate to reach out to the Batch team
by posting on the [Batch MSDN forum](https://social.msdn.microsoft.com/forums/azure/home?forum=azurebatch).
