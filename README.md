# A Miser's Guide to Defending Active Directory

## Summary
Belief: It is costly and difficult to build a cyber resilience program to protect Active Directory. 
Truth: Difficulty depends on more than we can address here. Cost, however, doesn't require as much. 

Defending Active Directory tends to circle around a few products and solutions, most of whom I'll leave their names out. We think of MFA, we think of Privileged Access Management, Vaulting, Just-in-Time (JIT), Just-Enough-Access (JEA), Certificates (PKI) and all these "solutions" to the various identity challenges. Unfortunately a lot of talks cover the "what" needs to be hardened and maybe shows an exploit or two, but few show what can be done quickly and effectively. Everyone stops and become stuck around SIEM solutions and ITDR threat solutions and EDR solutions. We then forget about actual resilience -- business resilience/BCDR and backups, monitoring and alerting, and general AD health.  The short of it is there is a lot to it and we're stuck boiling the ocean trying to make our 20 year old AD environments using "legacy" authentication suck less. 

I'm going to show you some tools, solutions, and approaches that can take your AD to a higher level without breaking the bank. So for the rest of this talk, we're going to think what would Ebenezer Scrooge Do to Secure his IT. 
