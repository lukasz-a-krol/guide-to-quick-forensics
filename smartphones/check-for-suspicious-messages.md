# Check for Suspicious Messages

Messages containing links are a common vector for malware infections.

![A message containing a link that infects the target with Cytrox Predator malware. Source: Citizen Lab](https://citizenlab.ca/wp-content/uploads/2021/12/Fig-7.png)

Links could be sent from any instant messaging apps or SMS. There are a few kinds of malicious links:

| Link target                                                             | Attacker goal                                       | Sophistication | Mitigation                                      |
| ----------------------------------------------------------------------- | --------------------------------------------------- | -------------- | ----------------------------------------------- |
| Phishing website, such as a webpage that looks like Google's login page | Trick user into entering personal data or passwords | Low            | Check webpage domain names and SSL certificates |
| App download                                                            | Convince user to download and install the app       | Low            | Don't install apps outside of app stores        |
| Webpage containing a browser exploit                                    | Exploit browser or app vulnerability                | High           | Don't click on links sent by unknown people     |