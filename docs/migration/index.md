---
title: "Migration"
description: App Center migration guide
author: glennwester
ms.author: glwest
ms.date: 02/03/2020
ms.topic: article
ms.assetid: FDA09DCF-92A4-423C-B18D-FB0A776DF39C
ms.service: vs-appcenter
---

# Migrating Existing Services

App Center is the next generation of HockeyApp and CodePush.

It provides a unified suite of capabilities that will greatly benefit a mobile app developer during their continuous delivery process of build, test and distribute to testers, while monitoring the app for crashes and user analytics. Some of these capabilities are built from ground-up while most others are using existing services like HockeyApp (Distribute & Crashes services) and Xamarin Test Cloud (Test service) under the hood.


<!-- ## [Microsoft CodePush](~/migration/codepush/index.md) Ian Geoghegan placeholder -->

## [Xamarin Insights](~/migration/xamarin-insights/index.md)

Visual Studio App Center is the next generation of Xamarin Insights, offering similar feature set and performance. After retirement, you must remove the Xamarin Insights SDK from your apps and move to the App Center SDK to ensure continuity.

## [App Center Auth](~/migration/auth/index.md)

App Center Auth has retired, and you must remove the App Center Auth SDK from your apps and move to [Microsoft Authentication Library (MSAL) SDK](https://docs.microsoft.com/azure/active-directory/develop/msal-overview). Learn more about [App Center's mobile backend retirement](https://devblogs.microsoft.com/appcenter/app-center-mbaas-retirement/). 

## [App Center Data](~/migration/data/index.md)

App Center Auth has retired, and you must remove the App Center Data SDK from your apps and move to [Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/). Learn more about [App Center's mobile backend retirement](https://devblogs.microsoft.com/appcenter/app-center-mbaas-retirement/).

## [App Center Push](~/migration/push/index.md)

App Center Auth has retired, and you must remove the App Center Push SDK from your apps and move to [Notification Hubs](https://docs.microsoft.com/azure/notification-hubs/). Learn more about [App Center's mobile backend retirement](https://devblogs.microsoft.com/appcenter/app-center-mbaas-retirement/).
