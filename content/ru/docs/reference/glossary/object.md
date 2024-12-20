---
title: Объект
id: object
date: 2023-11-20
full_link: /ru/docs/concepts/overview/working-with-objects/
short_description: >
   Сущность в системе Kubernetes, представляющая часть состояния кластера.
aka: 
tags:
- fundamental
---
Сущность в системе Kubernetes. Kubernetes использует их для представления состояния кластера. 
<!--more-->
Объект Kubernetes обычно представляет собой «запись о намерениях»: как только объект создан,
{{< glossary_tooltip text="управляющий слой" term_id="control-plane" >}} Kubernetes обеспечивает гарантию того,
что элемент, который этот объект представляет, действительно существует.
Создавая объект, вы фактически указываете системе Kubernetes, как должна
выглядеть эта часть рабочей нагрузки кластера; это желаемое состояние вашего кластера.
