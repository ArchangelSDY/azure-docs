---
title: Azure Government Marketplace | Microsoft Docs
description: This article provides guidance on how to use the Azure Government Marketplace.
services: azure-government
cloud: gov
documentationcenter: ''


ms.service: azure-government
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: azure-government
ms.date: 07/13/2018

---
# Azure Government Marketplace
The Azure Government Marketplace helps connect government agencies and partners with independent software vendors (ISVs) and start-ups that are offering their solutions in Azure Government.

> [!NOTE]
> For information on making your images available in Azure Government, see the [partner onboarding guidelines](documentation-government-manage-marketplace-partners.md).

## Variations
The Azure Government Marketplace differs from the Azure Marketplace in the following ways:
* Only Bring Your Own License (BYOL) and Pay-as-you-Go (PayGo) images are available.
* A different set of images is available. You can find the list of available images [here](./documentation-government-image-gallery.md) 

> [!NOTE]
> Red Hat Enterprise Linux is available in Azure Government with Azure Marketplace billing. This is a special case exception to the above statement about license options in Azure Government.

## Enable the Azure Government Marketplace
If your subscription is under an Enterprise Agreement (EA), the Azure Government Marketplace must be enabled before you can deploy a Marketplace solution to your subscription.
1. Log in to the [Enterprise Account Portal](https://ea.azure.com) as an Enterprise Administrator
1. Navigate to **Manage**
1. Under **Enrollment Details**, click the pencil icon next to the **Azure Marketplace** line item
1. Toggle **Enabled/Disabled** as appropriate
1. Click **Save**

> [!NOTE]
> It can take up to 24 hours for the change to take effect.  

## Deploy a Solution to your Subscription
1. **Log in** to the [Azure Government portal](https://portal.azure.us).

1. Click on **+New**.

   ![Screenshot shows Azure Government portal New page with Compute selected.](./media/government-manage-marketplace-launch.png)  

1. Browse through different products to find the right one. The marketplace publisher provides a list of certifications as part of the product description to help you make the right choice. 

   ![Screenshot shows marketplace Compute page and recommended apps.](./media/government-manage-marketplace-service.png)

1. Choose an product\image and click **Create**.

   ![Screenshot shows selected example Red Hat Enterprise Linux 7.2 description and the Create button.](./media/government-manage-marketplace-image.png)

1. Enter the required parameters for deployment.

   > [!NOTE]
   > In the Location dropdown, only Azure Government locations are visible
  
   ![Screenshot shows the Basics window with example parameters entered.](./media/government-manage-marketplace-deployment.png)

1. To start the provisioning process, click **Ok**.

## Next steps
* Subscribe to the [Azure Government blog](https://blogs.msdn.microsoft.com/azuregov/)
* Get help on Stack Overflow by using the [azure-gov](https://stackoverflow.com/questions/tagged/azure-gov) tag
* Give feedback or request new features via the [Azure Government feedback forum](https://feedback.azure.com/forums/558487-azure-government)