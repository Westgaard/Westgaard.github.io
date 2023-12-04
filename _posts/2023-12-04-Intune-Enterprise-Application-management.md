---
title: "Intune Enterprise Application management - an app store that (almost) works?"
date: 2023-12-04
---

Finally, an app store that (almost) works?
Microsoft just demonstrated its new "Enterprise Application Management" in Intune. Does it look good? Yes! Do we get autupdate of apps? Yes! (Partially) Does it cost way too much money? Yes! 🤑 

Enterprise Application Management is simply a new directory in Intune where we can pick Win32 applications that Microsoft has packed for us. By choosing an application, we automatically fill in all the information needed (With detection rules, etc.) to install the application, and do not even need to upload the installation file. It will of course be available as an addon, which costs about $2 per user, per month...

Application packaging and updating applications is a challenge all IT departments have, and if you ask me, application packaging is one of the stupidest things I know of (!). Unix has had Package Managers who have taken care of application installation with dependencies since 1995, while on Windows we package the same applications, in the same way, in different tenants. We have an attempt to put in place something similar with the Microsoft Store, but not all applications are made available here and there are some limited customization options.

Demonstration of Enterprise Application Management can be found here: [https://techcommunity.microsoft.com/t5/endpoint-management-events/navigate-the-future-of-enterprise-application-management-with/ec-p/3971683](https://techcommunity.microsoft.com/t5/endpoint-management-events/navigate-the-future-of-enterprise-application-management-with/ec-p/3971683)

This is certainly a promising product, and can in the long run provide good gains - but so far there are some gaps in the product that do not allow me to recommend it at that price.

And what I want this year for Christmas are some tips on how to handle application packaging or application updates in a better way 🎅🎁🎄
