---
# required metadata

title: Hazardous materials
description: This topic provides information about hazardous material documents and information that is stored in your environment.
author: t-benebo
ms.date: 01/10/2020
ms.topic: article
ms.prod: 
ms.technology: 

# optional metadata

ms.search.form:
# ROBOTS: 
audience: Application User
# ms.devlang: 
ms.reviewer: kamaybac
# ms.tgt_pltfrm: 
ms.custom: 19171
ms.assetid: 81fa3709-4ab8-4fbf-9806-359892a05985
ms.search.region: Global
ms.search.industry: Retail
ms.author: benebotg
ms.search.validFrom: 2019-10-14
ms.dyn365.ops.version: 

---

# Hazardous materials

[!include [banner](../includes/banner.md)]

Information about hazardous materials is set up in Product information management. This module also provides documents that can be printed through warehouse management.

When you ship materials that are classified as dangerous goods, additional paperwork must be included with the shipments. The hazardous materials functionality lets customers store classification information and relate it to release items. This information can then be used to help prepare shipping documentation.

> [!IMPORTANT]
> The hazardous materials features in Microsoft Dynamics 365 Supply Chain Management provide a collection of useful product information fields and related functionality that can help you record and reference information that is related to your hazardous products. These features can also help you design and print shipment documents that include some of the same information about any hazardous materials that you're shipping. However, the system won't automatically make you compliant with all applicable regulations in your country or region. Although these tools are intended to help you comply with common regulations, they are neither sufficient in themselves nor guaranteed to be so. Your organization is responsible for being aware of all applicable regulations and for taking all necessary steps to comply with them.

Before you can use this functionality, the following setup is required:

- **Product information management:** Set up codes that can be applied to released products.
- **Warehouse management:** Use additional shipping documents to print shipment information.

## Product information management

In Product information management, there is a range of setup tables where you can add the reference information that is provided in the dangerous goods lists for road, air, and sea freight.

Here are some of the regulations that are often referenced:

- **ADR** – Regulations that are related to the international carriage of dangerous goods by road
- **CFR 49** – Regulations in the United Sates for the carriage of dangerous goods
- **IMDG** – The International Marine Dangerous Goods (IMDG) code
- **IATA** – The International Air Transport Association (IATA) dangerous goods regulations

Each of these regulations has a dangerous goods list that includes reference codes. The lists for each type of transport are combined on shared international classifications. Supply Chain Management provides a reference table for the shared codes in those lists. Each list also has some unique codes that can be defined.

To start to configure this information, create a regulation that you can use to configure the initial parameters.

## Warehouse management

When a shipment is prepared, several new reports can be printed. These reports use the information that you set up in Product information management.


[!INCLUDE[footer-include](../../includes/footer-banner.md)]