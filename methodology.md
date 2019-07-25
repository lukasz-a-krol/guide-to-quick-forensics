# Methodology

The methodology for doing quick forensics can be quite ad-hoc, and eventually with time you will develop your own. This guide should help in this process. Generally, when trying to triage a possible infection, you will like for any anomaly that you are able to identify on the device. Such anomalies, for example, can be:

1. Applications and processes running on the device that you and the owner of the device do not recognize. Applications and processes that show some unusual characteristics, such as suspicious names and file locations, or attempts at hiding.
2. Because spyware normally would want to be able to survive a shutdown of the device, you will look for applications which maintain persistence over the device and are therefore registered for automatic execution at startup.
3. Suspicious network connections to infrastructure and services that you and the owner of the device do not recognize.

While it is not possible to compile an exhaustive checklist of precise anomalies to look out for, the process of developing a robust quick forensics methodology will require *training your eye*, by inspecting as many devices you can get your hands. Eventually, you will start recognizing patterns across various operating systems, and become more rapid and efficient at discarding legitimate applications and spotting those that stand out. It takes practice.

## Considerations on legal litigation

Under some circumstances, it is possible that the owner of the device has an interest in pursuing some legal action against the perpetrators of the attack you are documenting, or perhaps the producers of the technology used to conduct it. This could be the case, for example, with victims of domestic abuse, or perhaps with activists seeking to prove some illegal surveillance of their communications.

If you believe the person you are assisting might be interested in any form of legal litigation, especially based on your work, you might need to adapt your methodology. From country to country, from jurisdiction to jurisdiction, rules and best practices for gathering digital evidence admissible in court can vary. Generally, because of [chain of custody](https://en.wikipedia.org/wiki/Chain_of_custody) and to safeguard the integrity of the device, data acquisition (especially from phones) might be heavily restricted.

You should inform yourself about the laws and the standard practices from the jurisdiction you normally operate in. Ideally, you should seek advise from local forensics specialists and maybe even seek the assistance of an accredited forensics firm.