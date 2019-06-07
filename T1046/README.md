# Mappings

| Rules     |    SID    | Signature 		                                                      	    |  Verified |
| --------- | --------- | --------------------------------------------------------------------------------- | --------- |
| ET Open   |     *     | ET SCAN *                                                                         |    Yes    |
| ET Open   |     *     | GPL SCAN *									    |    Yes    |

# Notes

* Network Service Scanning - [T1046](https://attack.mitre.org/techniques/T1046/)

ET Open has several signatures, updated regularly, for the detection of this technique. All signatures are labeled as **ET SCAN A** or **GPL SCAN A**, where A equals the name of a particular service or scanning tool. 

Examples: 

- 2101638 - GPL SCAN SSH Version map attempt
- 2100321 - GPL SCAN Finger Account Enumeration Attempt
- 2024364 - ET SCAN Possible Nmap User-Agent Observed
- 2023687 - ET SCAN Acunetix scan in progress acunetix_wvs_security_test in http_uri
