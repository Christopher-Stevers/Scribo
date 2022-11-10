---
layout: layouts/post.njk
title: "Migrating wsl distro to D: drive"
description: "Using wsl when C: drive is full"
date: 2022-11-10T05:00:00.000Z
---
Check this out:https://dev.to/equiman/move-wsl-file-system-to-another-drive-2a3d

Make sure you reset your default user in /etc/wsl conf. This is needed to keep your vscode plugins working correctly.

You might want to back up your linux files before moving them, however I found that they were intact after I moved them.