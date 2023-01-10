# PROJECT NAME: python-tda-bug-hunt-2

# FEATURE: SmartFix for Python
The feature provides the minimum fix version of a given vulnerable direct that will solve the biggest amount of vulnerabilities on top of a Pull-Request

# DEPENDENCY
1. lyrebird==0.10.5


# VULNERABLE TRANSITIVE DEPENDENCIES
1. mitmproxy==4.0.3
2. cryptography==2.2.2


# VULNERABILITIES
1. mitmproxy==4.0.3 -> CVE-2018-14505
2. cryptography==2.2.2 -> CVE-2020-36242, CVE-2018-10903, CVE-2020-25659


# FIXED VERSION
1. lyrebird==1.18.0
