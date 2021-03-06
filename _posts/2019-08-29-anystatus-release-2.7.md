---
layout: post
title: AnyStatus Release 2.7
author: Alon Amsalem
date:   2019-08-29 15:00
redirect_from: "/2019/08/29/release-2.7.html"
tags: [New Releases]
---

AnyStatus 2.7 has been released and is available for download from our [Website](https://www.anystat.us/downloads), [Microsoft Store](https://www.microsoft.com/en-us/p/anystatus/9p044vpk62sb), and [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=anystatus.AnyStatus). This release includes several new widgets, bug fixes, and UI improvements.

## What's New

- Added a link to [Feedback](/feedback) page from the left menu. You're welcome to post your feedback through this page.
- Configuration settings encryption is now optional. You can now enable or disable encryption in the settings window. Encryption is enabled by default.
- Added sparkline chart to Upload and Download speed widgets.
- AnyStatus will now use a default name when adding new widgets.

## User Interface Improvements

- Removed window border.
- Replaced _Add Widget_ button icon in toolbar.
- Improved dark theme colors for widgets, toolbar and left menu.
- Cancelled success messages when importing or exporting settings.
- Renamed _Ok_ button to _Save_ in Settings window.
- Renamed Options to Settings in various places.

## Widgets

- System Information
  - Active TCP Connections
  - Logical Drive Usage
- Azure DevOps
  - Build
  - Release
  - Work Items
  - Work Items Query
  - Pull Requests

## Bug Fixes

- [#153](https://github.com/AnyStatus/Support/issues/153) Display correct temperature values on non-english machines in Weather widget.
- [#158](https://github.com/AnyStatus/Support/issues/158) Sparkline chart does not re-scale and goes off the widget boundaries.
- [#168](https://github.com/AnyStatus/Support/issues/168) Fix left menu background color in the light theme.

## API Changes

- Metric _Symbol_ property has been canceled and replaced with ToString method to enable custom symbols and formatting of Metric & Sparkline widgets display value. This is to allow the display value and sparkline chart scale to be different. For example, in Network Speed widget, the display value can be mega-bytes while the sparkline chart scale is bytes.

## Download

- Downloads: https://www.anystat.us/downloads
- Microsoft Store: https://www.microsoft.com/en-us/p/anystatus/9p044vpk62sb
- Visual Studio Marketplace: https://marketplace.visualstudio.com/items?itemName=anystatus.AnyStatus

## Summary

That's it for this release. Feel free to leave a comment and let me know what you think.
