---
title: Should I use Microsoft Account or Azure Active Directory? 
description: The admin has both an MSA and Azure AD account but doesn't know which one to use
comment:  As of August 2023 this include is used to render marketing FAQ content for VS Subscriptions in the following portals - VSCom, Manage, and My portals. It was not used for learn.microsoft.com content at that time.  SMEs are Evan Windom and Larissa Crawford of Red Door Collaborative and Sharvari Dighe.
ms.topic: include
ms.assetid: 8cb1b018-b97a-42e9-a71e-68e60cb8cec1
author: evanwindom
ms.author: amast
ms.date: 08/18/2023
user.type: admin
tags: msa
subscription.type: vl, cloud, retail, partner
sap.id: 17a2bf94-0d03-2629-dfd8-e8935f9126ec
---

## Should I use Microsoft Account (MSA) or Azure Active Directory (Azure AD)?

An MSA is an email account owned by a subscriber to access Microsoft services. If they leave your company, they can still access services that are connected to that identity. Until access is manually removed in the admin portal, they can continue using an assigned Visual Studio subscription or manage agreements if they're an admin.

Azure AD is a cloud-based tenant managed by your organization. An Azure AD account can be used to control access to Microsoft services. When a subscriber leaves the company and their account is deactivated, they can no longer sign in with this email address.

We recommend using Azure AD since the admin portal can automatically manage unauthorized access. When you deactivate a person's account in Azure AD, access to a subscription or the admin portal is also blocked. 
