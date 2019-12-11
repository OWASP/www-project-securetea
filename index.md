---

layout: col-sidebar
title: OWASP SecureTea Project
site_side: true
tags: securetea
project: true
level: 4
type: tool

---
<!-- rebuild 40 -->

<h1> OWASP SecureTea</h1>
<h4 align="left">One stop security solution for your device<a href="https://github.com/OWASP/SecureTea-Project" target="_blank"></a></h4>

[![Build Status][Travis-badge]][Travis]
[![Codacy Badge][Codacy-badge]][Codacy]
[![PyPI][PyPi-badge]][PyPi]
[![GitHub][License-badge]][License]
[![Telegram][Telegram-badge]][Telegram]
[![Version][Version-badge]][Version]
[![Tag][Tag-badge]][Tag]
[![GitHub issues][Issues-badge]][Issues]
[![GitHub pull requests][PR-badge]][PRs]
[![GSOC 2019][GSOC-2019-badge]][GSOC-OWASP]
[![Follow Us](https://img.shields.io/twitter/url/https/secureteatool.svg?label=SecureTea%20Project&style=social)](https://twitter.com/secureteatool)
[![All Contributors](https://img.shields.io/badge/all_contributors-8-orange.svg?style=flat-square)](#contributors)
[![Heroku][Heroku]](https://secure-tea.herokuapp.com/)
## Description
**The OWASP SecureTea Project** provides a one-stop security solution for various devices (personal computers / servers / IoT devices).

## Features

- [x] [Intrusion Detection System](/doc/en-US/user_guide.md#intrusion-detection-system)
- [x] [Firewall](/doc/en-US/user_guide.md#firewall)
- [x] [AntiVirus](/doc/en-US/user_guide.md#antivirus)
- [x] [Server Log Monitor](/doc/en-US/user_guide.md#server-log-monitor)
- [x] [System Log Monitor](/doc/en-US/user_guide.md#system-log-monitor)
- [x] [Local Web Deface Detection & Prevention System](/doc/en-US/user_guide.md#web-deface-detection)
- [x] [Auto Web Server Patcher](/doc/en-US/user_guide.md#auto-server-patcher)
- [x] [Insecure Headers Detection](/doc/en-US/user_guide.md#insecure-headers)
- [x] [IoT Anonymity Checker](/doc/en-US/user_guide.md#iot-anonymity-checker)
- [x] [Auto Report Generation Using OSINT](/doc/en-US/user_guide.md)
- [x] [Notifying Suspicious Activities Using Various Mediums (Twitter, Telegram, Slack, Gmail, SMS, AWS)](doc/en-US/user_guide.md#setting-up-notifiers)
- [x] [Interactive GUI For Ease Of Setting Up](/doc/en-US/user_guide.md#configuring-using-web-ui)

## Installation

Before installing, please make sure to install the **[pre-requisites](/doc/en-US/user_guide.md#pre-requisites)**.

You can install SecureTea from PyPi package manager using the following command:

`$ sudo python3 -m pip install securetea`

**or**

You can install SecureTea using the latest repository:

```shell
git clone https://github.com/OWASP/SecureTea-Project.git
cd SecureTea-Project/
sudo python3 -m pip install -r requirements.txt
sudo python3 setup.py install
```

Please make sure all dependencies are installed if anyone of the above fails.

For more detailed information, refer to the [installation guide](/doc/en-US/user_guide.md#installation).


