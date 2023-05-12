---
title: "Logical processors for Company Portal"
date: 2023-05-12
---

I have several VMs enrolled in Intune, but some of them didn't have the Company Portal installed. Upon reviewing the Device Install Status in Intune, it appears that I was a bit conservative when creating the Win10 VMs and only allocated one logical processor:
![LogicalProcessorsCompanyPortal](/docs/assets/LogicalProcessorsCompanyPortal.png)

I used the Company Portal from the Microsoft Business Store (New), which doesn't allow much configuration in terms of requirements:

![LogicalProcessorsCompanyPortal](/docs/assets/CompanyPortalNewConfig.png)


However, after shutting down the VM and adding an additional virtual processor in Hyper-V, the issue was resolved. Note to self when creating new Win10-VMs...
