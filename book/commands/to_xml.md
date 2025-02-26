---
title: to xml
layout: command
version: 0.59.1
usage: |
  Convert table into .xml text
---

# `{{ $frontmatter.title }}`

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> to xml --pretty```

## Parameters

 -  `--pretty {int}`: Formats the XML text with the provided indentation setting

## Examples

Outputs an XML string representing the contents of this table
```shell
> { "note": { "children": [{ "remember": {"attributes" : {}, "children": [Event]}}], "attributes": {} } } | to xml
```

Optionally, formats the text with a custom indentation setting
```shell
> { "note": { "children": [{ "remember": {"attributes" : {}, "children": [Event]}}], "attributes": {} } } | to xml -p 3
```
