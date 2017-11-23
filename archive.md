---
layout: page
title: Archived Posts
sidebar_link: true
---

This is a page that links to all archived/old posts from Medium.

{% assign archive_files = site.static_files | where: "archive", true | reverse %}

{% for archive_file in archive_files %}
  <a href = "{{archive_file.path}}">{{archive_file.name}}</a>

{% endfor %}
