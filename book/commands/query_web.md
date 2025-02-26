---
title: query web
layout: command
version: 0.59.1
usage: |
  execute selector query on html/web
---

# `{{ $frontmatter.title }}`

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> query web --query --as-html --attribute --as-table --inspect```

## Parameters

 -  `--query {string}`: selector query
 -  `--as-html`: return the query output as html
 -  `--attribute {string}`: downselect based on the given attribute
 -  `--as-table {any}`: find table based on column header list
 -  `--inspect`: run in inspect mode to provide more information for determining column headers
