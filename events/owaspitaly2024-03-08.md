---

layout: col-sidebar
title: OWASP Italy March Meetup
tags: event, Italy
level: 0
site_side: true
region: Europe

---

The OWASP Italy March 2024 Meetup will be a virtual event on March 8th, 2024. This is a free, informal event, aimed at increasing awareness and knowledge of web application security. The event was primarily intended to appeal to security professionals, software developers, software quality engineers, and computer science students with a strong interest in computer security. The goal of the event was to stimulate interest in web application security, secure software engineering practices and foster new initiatives within organizations.

### PROGRAM

The event will take place from 4 PM to 6 PM (CET time) over Zoom. We are delighted to announce a strong program featuring 3 distinguished experts in the field of cybersecurity:

| Time          | Speakers                                                                           | Title                                                                  |
| :---          | :---                                                                               | :---                                                                   |
| 16.00 - 16.15 | Davide Ariu (Pluribus One) and Matteo Meucci (IMQ Minded Security)                 | Welcome and opening by the OWASP Italy chairs                          |
| 16.15 - 17.00 | Tommaso Innocenti                                                                  | OAuth 2.0 Redirect URI Validation Falls Short,Literally                |
| 17.00 - 17.45 | Luca Demetrio, Andrea Valenza                                                      | Automatically Test (and Sometimes Bypass) Web Application Firewalls    |


### REGISTRATION

The event is free but you need to register here: [OWASP Italy Meetup](https://www.meetup.com/it-IT/owasp-italy-meetup-group/). We encourage participants to subscribe to the meetup to be informed about future events organized by the chapter.

### SPEAKERS
#### Tommaso Innocenti
Talk: OAuth 2.0 Redirect URI Validation Falls Short, Literally

Abstract:
OAuth 2.0 requires a complex redirection trail between websites and Identity Providers (IdPs). In particular, the "redirect URI" parameter included in the popular Authorization Grant Code flow governs the callback endpoint to which users are routed, together with their security tokens.
In this talk, I will present recent attack trends in conjunction with the research trends to identify the source of the problem that allowed us to generate our hypothesis.
Based on this observation, I will present novel attack techniques and the experiment that allowed us to verify that the OAuth 2.0 security guidance is under-specified empirically. Finally, I will explain end-to-end attack scenarios that combine our attack techniques with common web application vulnerabilities, ultimately resulting in a complete compromise of the secure delegated access that OAuth 2.0 promises.

#### Luca Demetrio, Andrea Valenza
Talk: "Automatically Test (and Sometimes Bypass) Web Application Firewalls"
Abstract
Web Application Firewalls (WAFs) are hugely popular since they block (most) attacks with low maintenance effort. However, testing their effectiveness can be challenging, often involving a trade-off between the speed of automatic testing and the precision of manual testing.
In this talk, we will show you an alternative approach that connects both worlds, by automatically testing a WAF with tools capable of creating new payloads on the fly, based on the responses of the WAF itself.
We will showcase WAF-A-MoLE, a tool customized to create evasive SQL injections via guided mutation fuzzing, both against ModSecurity and Next Generation WAFs using machine learning at their core.

### ORGANIZERS
- Matteo Meucci, OWASP Italy Chair & IMQ Minded Security
- Davide Ariu, OWASP Italy Chair & Pluribus One

Back to the [OWASP-Italy Chapter](https://owasp.org/www-chapter-italy)
