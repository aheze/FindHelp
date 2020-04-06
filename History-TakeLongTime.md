---
title: Finding from History takes a long time
---

# Why does finding from History take so long?
Just to double check, make sure you hit the `search` button on the keyboard. Why? If a photo is not cached, results will only appear after you tap `search`.

Anyways, when you find from History, Find performs an OCR (Optical Character Recognition) request. If you're only finding from a couple photos, it might not take long, but if you're finding from your entire history, expect results in 20~ish seconds.

This issue came up during development, so we also made a solution. Try [Caching](/History-WhatIsTheCache.md)! When you cache photos, Find pre-searches them for text, so when you search in them later, results will pop up _instantly_. Like that \*snap\*
