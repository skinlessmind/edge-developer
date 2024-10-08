---
title: What's New in DevTools (Microsoft Edge 128)
description: "Updated labels for selector stats. Fixed whitespace in Activity Bar right-click menus. And more."
author: MSEdgeTeam
ms.author: msedgedevrel
ms.topic: conceptual
ms.service: microsoft-edge
ms.subservice: devtools
ms.date: 08/22/2024
---
# What's New in DevTools (Microsoft Edge 128)

[!INCLUDE [Microsoft Edge team note for top of What's New](../../includes/edge-whats-new-note.md)]


<!-- ====================================================================== -->
## Updated labels for selector stats

<!-- Subtitle: Use the "Enable CSS selector stats" setting instead of the "Enable advanced paint instrumentation (slow)" to capture CSS selector statistics for Recalculate Style events -->

In the **Performance** tool, the duplicate **Selector Stats** label has been removed from the `Recalculate Style` event details.  Selector stats can be enabled by using the dedicated setting for it.

Also, the **Enable advanced rendering instrumentation (slow)** setting has been renamed back to **Enable advanced paint instrumentation (slow)**.  Previously, this setting was used for both paint instrumentation and selector stats.  This setting label has been updated because there's now a dedicated setting for selector stats.

Before:

![Old selector stats labels](./devtools-128-images/old-selector-stats.png)

After:

![New selector stats labels](./devtools-128-images/new-selector-stats.png)


<!-- ====================================================================== -->
## Fixed whitespace in Activity Bar right-click menus

<!-- Subtitle: Header titles in the top of the Activity Bar's right-click menus have been restored. -->

In recent versions of Microsoft Edge, some context menus in the **Activity Bar** displayed empty whitespace in the header area at the top:

![Old context menu header](./devtools-128-images/missing-header-title.png)

The top of each context menu now shows the title again:

![New context menu header](./devtools-128-images/header-title.png)


<!-- ====================================================================== -->
## Announcements from the Chromium project

Microsoft Edge 128 also includes the following updates from the Chromium project:

* [Performance panel updates](https://developer.chrome.com/blog/new-in-devtools-128#perf)
   * [Enhanced Network track](https://developer.chrome.com/blog/new-in-devtools-128#perf-network)
   * [Customized performance data with extensibility API](https://developer.chrome.com/blog/new-in-devtools-128#perf-extension)
   * [Details in the Timings track](https://developer.chrome.com/blog/new-in-devtools-128#timings-details)
* [Copy all listed requests in the Network panel](https://developer.chrome.com/blog/new-in-devtools-128#copy-all-listed)
* [Faster heap snapshots with named HTML tags and less clutter](https://developer.chrome.com/blog/new-in-devtools-128#heap-snapshots)
* [Open Animations panel to capture animations and edit @keyframes live](https://developer.chrome.com/blog/new-in-devtools-128#animations)


<!-- ====================================================================== -->
<!-- uncomment if content is copied from developer.chrome.com to this page -->

<!-- > [!NOTE]
> Portions of this page are modifications based on work created and [shared by Google](https://developers.google.com/terms/site-policies) and used according to terms described in the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0).
> The original page for announcements from the Chromium project is [What's New in DevTools (Chrome 128)](https://developer.chrome.com/blog/new-in-devtools-128) and is authored by [Sofia Emelianova](https://developers.google.com/web/resources/contributors) (Senior Technical Writer working on Chrome DevTools at Google). -->


<!-- ====================================================================== -->
<!-- uncomment if content is copied from developer.chrome.com to this page -->

<!-- [![Creative Commons License](../../../../media/cc-logo/88x31.png)](https://creativecommons.org/licenses/by/4.0)
This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0). -->
