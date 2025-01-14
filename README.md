# Grandstream Exploits

Below are working PoCs for a bunch of remote code execution vulnerabilties that I found in a range of Grandstream devices.


| CVE | Model        | Device Type | Vulnerability           | Affected Versions  |
| -----|-------------:|:------:|:-------------:| -----:|
| CVE-2019-10655 | GAC2500      |Audio Conferencing Unit| Unauthenticated RCE | <= 1.0.3.35 |
| CVE-2019-10655 | GVC3202      |Video Conferencing Unit | Unauthenticated RCE | < 1.0.3.51 |
| CVE-2019-10655 | GXV3275      | IP Video Phone | Unauthenticated RCE | < 1.0.3.219 |
| CVE-2019-10655 | GXV3240      | IP Video Phone | Unauthenticated RCE | < 1.0.3.219 |
| CVE-2019-10655 | GXP2200*     | IP Video Phone | Unauthenticated RCE | <= 1.0.3.27 |
| CVE-2019-10659 | GXV3370      | IP Video Phone | Authenticated RCE | < 1.0.1.41|
| CVE-2019-10656 | GWN7000      | Enterprise Router | Authenticated RCE |< 1.0.6.32 |
| CVE-2019-10658 | GWN7610      | WiFi Access Point | Authenticated RCE | < 1.0.8.18 |
| CVE-2019-10660 | GXV3611IR_HD |IP Camera   | Authenticated RCE|  < 1.0.3.23 |
| CVE-2019-10662 | UCM62xx |IP PBX   | Authenticated RCE | < 1.0.19.20 |
| CVE-2019-10659 | WP820 | Enterprise WiFi IP Phone | Authenticated RCE | < 1.0.3.6 |


\* Unpatched due to end of life product.

