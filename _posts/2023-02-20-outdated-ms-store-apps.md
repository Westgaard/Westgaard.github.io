---
title: "Outdated apps in MS Store (new) in Intune"
date: 2023-02-20
---

In november 2022 [MS Store (new)](https://learn.microsoft.com/en-us/mem/intune/fundamentals/whats-new#week-of-november-28-2022) was available in Intune, and to cite Microsoft:
> You can now search, browse, configure, and deploy Microsoft Store apps within Intune. The new Microsoft Store app type is implemented using the Windows Package Manager. This app type features an expanded catalog of apps, which includes both UWP apps and Win32 apps.

![VLC MS Store (new)](/docs/assets/vlc-msstore.png)

The process of adding apps from MS Store (new) to Intune is much easier than before, and it's overall a big improvement.
However, be cautions and pay attention to the versions that get installed. Take VLC for example, the version installed from MS Store (new) is 3.0.16, which is from june 2021...

![VLC installed](/docs/assets/vlc-installed.png)
![VLC versions](/docs/assets/vlc-versions.png)

And it is subsequentcly blocked by Windows Defender.

![VLC blocked](/docs/assets/vlc-blocked.png)
