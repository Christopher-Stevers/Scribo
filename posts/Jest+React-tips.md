---
layout: layouts/post.njk
title: Forest Bower VII
description: ""
date: 2022-09-57T12:27:00.000Z
---

## Cannot update state on unmounted component.
Solution to this is to wrap end of test in ```waitFor(()=>{})``` I assume this works because it prevents jest from trying to unmount the component before the state updater runs. I've looked everywhere and can't find another solution.
