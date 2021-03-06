---
title: Manage permissions to resources per user in Azure Stack | Microsoft Docs
description: As a service administrator or tenant, learn how to manage RBAC permissions.
services: azure-stack
documentationcenter: 
author: Heathl17
manager: byronr
editor: 
ms.assetid: cccac19a-e1bf-4e36-8ac8-2228e8487646
ms.service: azure-stack
ms.workload: na
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.date: 09/25/2017
ms.author: helaw
ms.translationtype: HT
ms.sourcegitcommit: c3a2462b4ce4e1410a670624bcbcec26fd51b811
ms.openlocfilehash: 1e0ced4b2d65456034ba3f8543152702c089a0b0
ms.contentlocale: pt-br
ms.lasthandoff: 09/25/2017

---
# <a name="manage-role-based-access-control"></a>Manage Role-Based Access Control

*Applies to: Azure Stack integrated systems and Azure Stack Development Kit*

A user in Azure Stack can be a reader, owner, or contributor for each instance of a subscription, resource group, or service. For example, User A might have reader permissions to Subscription 1, but have owner permissions to Virtual Machine 7.

* Reader: User can view everything, but can’t make any changes.
* Contributor: User can manage everything except access to resources.
* Owner: User can manage everything, including access to resources.

## <a name="set-access-permissions-for-a-user"></a>Set access permissions for a user
1. Sign in with an account that has owner permissions to the resource you want to manage.
2. In the blade for the resource, click the **Access** icon ![](media/azure-stack-manage-permissions/image1.png).
3. In the **Users** blade, click **Roles**.
4. In the **Roles** blade, click **Add** to add permissions for the user.

## <a name="next-steps"></a>Next steps



