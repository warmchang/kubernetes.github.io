---
# Removed from Kubernetes
title: SelectorIndex
content_type: feature_gate

_build:
  list: never
  render: false

stages:
  - stage: alpha 
    defaultValue: false
    fromVersion: "1.18"
    toVersion: "1.18"
  - stage: beta 
    defaultValue: true
    fromVersion: "1.19"
    toVersion: "1.19"
  - stage: stable
    defaultValue: true
    fromVersion: "1.20"
    toVersion: "1.25"

removed: true  
---

<!--
Allows label and field based indexes in API server watch cache to accelerate
list operations.
-->
允许使用 API 服务器的 watch 缓存中基于标签和字段的索引来加速 list 操作。
