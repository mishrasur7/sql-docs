---
author: rwestMSFT
ms.author: randolphwest
ms.reviewer: vanto
ms.date: 10/31/2023
ms.service: sql
ms.subservice: linux
ms.topic: include
ms.custom:
  - linux-related-content
---
You should run production workloads on supported platforms like [Red Hat Enterprise Linux](https://www.redhat.com/technologies/linux-platforms/enterprise-linux/sql-server), [SUSE Linux Enterprise Server](https://www.suse.com/c/microsoft-sql-server-on-suse-linux-enterprise-server-new-suse-best-practices), and [Ubuntu Pro](https://ubuntu.com/blog/microsoft-sql-server-on-ubuntu), as they receive regular OS security updates, and have support coverage options that you need for enterprise database deployments.

| Platform | File system | Installation guide | Get |
| --- | --- | --- | --- |
| Red Hat Enterprise Linux 8.x Server (and 9.x Server in preview) | XFS or EXT4 | [Installation guide](../quickstart-install-connect-red-hat.md) | [Get RHEL 8](https://access.redhat.com/products/red-hat-enterprise-linux/evaluation) |
| SUSE Enterprise Linux Server v15 (SP1 - SP4) | XFS or EXT4 | [Installation guide](../quickstart-install-connect-suse.md) | [Get SLES v15](https://www.suse.com/products/server) |
| Ubuntu 20.04 (and 22.04 in preview) | XFS or EXT4 | [Installation guide](../quickstart-install-connect-ubuntu.md) | [Get Ubuntu 20.04](https://releases.ubuntu.com/20.04/) |
| Docker Engine 1.8+ on Linux | N/A | [Installation guide](../quickstart-install-connect-docker.md) | [Get Docker](https://www.docker.com/get-started) |

> [!TIP]  
> For more information, review the [system requirements](../sql-server-linux-setup.md#system) for [!INCLUDE [ssnoversion-md](../../includes/ssnoversion-md.md)] on Linux. For the latest support policy for [!INCLUDE [ssNoVersion](../../includes/ssnoversion-md.md)], see the [Technical support policy for Microsoft SQL Server](/troubleshoot/sql/general/support-policy-sql-server).
