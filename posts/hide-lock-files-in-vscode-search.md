---
layout: layouts/post.njk
title: Hide lock files
description: How to hide lock files in vscode.
date: 2022-10-25T05:00:00.000Z
featuredImage: ![image](https://user-images.githubusercontent.com/72156679/197763484-df4db56b-91f0-4401-bdb5-98de5f60c258.png)
---

You've been there before - trying to quickly search something up in vscode and all you can see is miles of lock file until you close the little dropdowny things beside the lock file name.
Why not just exclude them from search? Because its to hard! No, it isn't, its just a few steps and will save you time.
- Go to the top menu then File>Preferences>Settings and pick the user tab
- Search `search exclude`. Scroll down and you'll a box like this
![image](https://user-images.githubusercontent.com/72156679/197761275-f21aa933-5c87-4898-96d4-5f4368872ab8.png)
Click `Add Pattern` and type in package-lock.json. Once that's been added if you have a yarn.lock file you can do the same for `yarn.lock`.
Hooray, now you can actually find code that has a similar name to your dependency!
