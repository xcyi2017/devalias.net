---
layout: post
title: ERPScan Automator - Because Manual is Meh
date: '2013-08-10T08:00:50+10:00'
tags:
- wrpscan
- sap
- automation
- script
- gist
- hack
- pentest
categories:
- devalias
tumblr_url: http://devalias.tumblr.com/post/57768165029/erpscan-automator-because-manual-is-meh
redirect_from: /post/57768165029/erpscan-automator-because-manual-is-meh
disqus: true
webmention: true
crosspost_to_medium: false
---
Another quick little tool for you guys today that I hacked together to save myself some time. This one automates running through a number of tests using the [ERPScan SAP Pentesting Tool](https://erpscan.com/research/free-pentesting-tools-for-sap-and-oracle/)

At time of writing, configuration is all done inside the script, with no support for command line parameters (might add them in the future)

{% gist alias1/6118709 %}
