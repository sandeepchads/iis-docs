---
title: "SilverStripe CMS FAQ | Microsoft Docs"
author: rick-anderson
description: "WebMatrix supports installing open source community applications from the Web Application Gallery, and publishing to hosting providers, including a set of Be..."
ms.author: iiscontent
manager: soshir
ms.date: 07/06/2010
ms.topic: article
ms.assetid: 376a2ffa-1dde-4527-9f83-1bfcd276d8b6
ms.technology: iis-develop
ms.prod: iis
msc.legacyurl: /learn/develop/installingpublishing-apps-with-webmatrix/silverstripe-cms-faq
msc.type: authoredcontent
---
SilverStripe CMS FAQ
====================
by Faith A

WebMatrix supports installing open source community applications from the Web Application Gallery, and publishing to hosting providers, including a set of Beta partner hosting providers. This FAQ contains information about installing and publishing, as well as any issues that may occur after publishing.

## Installing and Publishing SilverStripe CMS

#### Q: How do I install SilverStripe CMS?

A: To install SilverStripe CMS, use the following steps:

1. Open WebMatrix and select **Site from Web Gallery**.
2. Select the **CMS** category on the left-hand side.
3. Find **SilverStripe CMS** in the list and install it.
4. In any workspace, on the **Home** tab, in the **Site** group, click **Run** or press F12 to open the site in your default web browser.
5. Follow the instructions to complete installation.

#### Q: How do I publish my SilverStripe CMS website?

A: To publish a SilverStripe CMS website, use the following steps:

1. In any workspace, on the **Home** tab, in the **Site** group, click **Publish**.
2. On the **Publishing Settings** dialog, enter the server info you received from your web host.
3. Click **Validate Connection** to ensure that the settings are correct.
4. Click **Publish**.
5. If you have not published your database before, select the Database checkbox.
6. After previewing the changes, click **Continue**.

## Known Issues

**Issue:** Silverstripe CMS gives a "HTTP 500 PHP FCGI Error" when you download a published site  
**Workaround:** Skip the silverstripe-cache/manifest\_main in Publish Preview after you click on "Download published site …". This file is used for caching purposes and is specific to each computer.