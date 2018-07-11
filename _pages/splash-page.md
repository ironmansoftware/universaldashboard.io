---
title: "Universal Dashboard"
layout: splash
permalink: /
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/splash.jpg
  cta_label: "Download"
  cta_url: "https://www.powershellgallery.com/packages/UniversalDashboard"
  caption: ""
excerpt: "Universal Dashboard is a cross-platform PowerShell module for developing and hosting web-based, interactive dashboards."
intro: 
  - excerpt: ''
feature_row:
  - image_path: assets/images/chart.gif
    alt: "chart"
    title: "Create websites with your existing PowerShell skills"
    excerpt: "Build dynamic websites to display data in controls like charts, tables and grids as dashboards for your whole organization. Take it a step further and build fully customizable web interfaces around your existing PowerShell logic. No need to learn JavaScript, HTML or CSS. Build websites just like you would build desktop apps."
    url: "https://docs.universaldashboard.io/concepts"
    btn_label: "View the Docs"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/login.png
    alt: "login"
    title: "Security Built in"
    excerpt: "Lock down your websites with first-class security built in. Allow users to authenticate with OAuth providers like Facebook, Microsoft and Google or provide an internal authentication system like Active Directory. Lock down your REST APIs with JSON web tokens."
    url: "https://docs.universaldashboard.io/login-pages"
    btn_label: "View the Docs"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/azure.png
    title: "Host it anywhere"
    excerpt: "Universal Dashboard is cross-platform and can run anywhere PowerShell Core and ASP.NET Core is available. Host in Azure, IIS, as a Windows Service or simply the command line. Take advantage of Docker containers or jump into IoT with Raspberry Pi. Run in your existing infrastructure on Windows PowerShell. Universal Dashboard supports PowerShell v5.1+."
    url: "https://docs.universaldashboard.io/running-dashboards"
    btn_label: "View the Docs"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row type="right" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}