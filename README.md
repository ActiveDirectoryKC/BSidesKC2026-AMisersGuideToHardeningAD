# A Miser's Guide to Defending Active Directory

## Summary
Belief: It is costly and difficult to build a cyber resilience program to protect Active Directory. 
Truth: Difficulty depends on more than we can address here. Cost, however, doesn't require as much. 

Defending Active Directory tends to circle around a few products and solutions, most of whom I'll leave their names out. We think of MFA, we think of Privileged Access Management, Vaulting, Just-in-Time (JIT), Just-Enough-Access (JEA), Certificates (PKI) and all these "solutions" to the various identity challenges. Unfortunately a lot of talks cover the "what" needs to be hardened and maybe shows an exploit or two, but few show what can be done quickly and effectively. Everyone stops and become stuck around SIEM solutions and ITDR threat solutions and EDR solutions. We then forget about actual resilience -- business resilience/BCDR and backups, monitoring and alerting, and general AD health.  The short of it is there is a lot to it and we're stuck boiling the ocean trying to make our 20 year old AD environments using "legacy" authentication suck less. 

I'm going to show you some tools, solutions, and approaches that can take your AD to a higher level without breaking the bank. So for the rest of this talk, we're going to think what would Ebenezer Scrooge Do to Secure his IT. 

## Disclosure
While I strive to make sure all content here is accurate, I am not infallable. Please use caution when implementing or deploying the solutions or using the resources outlined or talked about in this. At the end of the day, you are responsible for yourself and I cannot take any responsiblity and offer no warranty for anything in this document. 

The views and ideas presented in this document/documents are my own and are not a reflection or an endorsement by my employer or employers. Vendors were not consulted before their products were mentioned so any recommendations or reviews are solely my own. 

## LLM Disclosure
I wrote all of this myself. I did use LLMs to check the content, help me organize, and proof, but all the content is 100% mine. Any images used fall under fair use and attributions are included in the [attributions.md](https://github.com/ActiveDirectoryKC/BSidesKC2026-AMisersGuideToHardeningAD/blob/main/Attributions.md) file. 
All scripts are mine or attributed to their authors. 
