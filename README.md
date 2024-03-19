# Threat Intelligence Model for Phishing using STIX

Using threat intelligence tools to showcase how an APT (advanced persistent threat) would use phishing to target an organization. This project is an example of using STIX (Structured Threat Information eXpression). You can find more information at [oasis](https://oasis-open.github.io/cti-documentation/stix/examples.html).

## Stix TTP Scenario

Using STIX to showcase we can emulate an attack. In this case, APT-Random is exploiting University of X.

- Tactic: Goal of APT-Random is to exploit and gain access sensitive information from higher education institution, Universtiy of X.
- Technique: APT-Random uses phishing as a means to gain initial access within University X
- Procedure: APT-Random uses gophish to construct fake spear phishing emails and send them across the university with an attachment that would install a malware known as Bandock.
