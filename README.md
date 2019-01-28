# Mapping NSM rules to MITRE ATT&CK Techniques 

## About

The idea behind this project is to categorize and develop, where feasible, Suricata *(and general NSM)* rules by mapping them against the [MITRE ATT&CK framework](https://attack.mitre.org). 

### How does it work?

Each technique has its own folder. Inside the folder, one of two things can happen:

* We will link to existing rules from known rulesets if a rule already exists
* We will share the rule in the format used by Suricata

**The following rulesets are currently considered by this project:**

* [Emerging Threats Open](https://rules.emergingthreats.net/open/suricata-4.0/)

## Have something to share? 

Feel free to reach out to me via Twitter ([@0xtf](https://twitter.com/0xtf)) if you have some rules you'd like to share or comments/questions/tips.

## MITRE ATT&CK Navigator

Browse supported techniques using [this URL](https://mitre-attack.github.io/attack-navigator/enterprise/#layerURL=https%3A%2F%2Fraw.githubusercontent.com%2F0xtf%2Fnsm-attack%2Fmaster%2FNSM_Rules.json).

The Navigator layer will include the applicable Signature ID's that provide coverage for a certain technique. 
