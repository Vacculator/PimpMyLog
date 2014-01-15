---
layout: default
title: Debug
---

# Introduction

There is a modest tool:

- to help you build complex RegEx
- to help me to help you!

# Install

This tool is deactivated by default and you need explicitly to activate it because it can contain some confidential informations about your configuration, about your *PHP* installation, ...

The tool is `inc/test.php`. If you directly call it in your browser, it will fail and ask you to copy the file to `inc/test.REMOVE_UPPERCASE.php`. Do it and load in your browser <http://.../PimpMyLog/inc/test.REMOVE_UPPERCASE.php>.

# Uninstall

When you have finished with this tool, **remove** file `inc/test.REMOVE_UPPERCASE.php`!

# Regex tester

This is the most interesting part :-) It will help you to build RegExs to match your log files.

{% image /assets/ss/regextester.png class="img-responsive" alink="" atarget="" %}

Usage is quite simple :

- enter a log line that you want to match in the *Log* text area
- write your magical RegEx in the *RegEx* area
- write your `match` array in the *Match* area

Click on the *Test* button and *Pimp My Log* will use the same parser as the main log viewer to decode. Once your *RegEx* and `match` array are right, you can use them in your configuration file.

# Regex samples

These samples are just for testing purpose...

# Configuration

If you experience some issues and can give us access to this page remotely, we will take a look on this panel to :

- display your current configuration file
- get informations about your current configuration file
- display rights for all log files defined by the configuration file
- your *PHP* configuration














