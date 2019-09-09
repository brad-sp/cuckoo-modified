This is a heavily modified version of [Cuckoo Sandbox](http://www.cuckoosandbox.org) provided under the GPL.

It offers a number of advantages over the upstream Cuckoo:
+ Fully-normalized file and registry names
+ 64-bit analysis
+ Handling of WoW64 filesystem redirection
+ Many additional API hooks
+ Service monitoring
+ Correlates API calls to malware call chains
+ Ability to follow APC injection and stealth explorer injection
+ Pretty-printed API flags
+ Per-analysis Tor support
+ Over 150 new signature modules (over 75)
+ Anti-anti-sandbox and anti-anti-VM techniques built-in
+ More stable hooking
+ Ability to restore removed hooks
+ Greatly improved behavioral analysis and signature module API
+ Ability to post comments about analyses
+ Deep hooks in IE's JavaScript and DOM engines usable for Exploit Kit identification
+ Automatic extraction and submission of interesting files from ZIPs, RARs, RFC 2822 emails (.eml), and Outlook .msg files
+ Direct submission of AV quarantine files (Forefront, McAfee, Trend Micro, Kaspersky, MalwareBytes, MSE/SCEP, and SEP12 formats currently supported)
+ Automatic malware classification by [Malheur](http://mlsec.org/malheur/)
+ Significant contributions from [Jeremy Hedges](https://github.com/killerinstinct/), [William Metcalf](https://github.com/wmetcalf), and Kevin Ross
+ Hundreds of other bugfixes

Since I will no longer have access to this account, I have created a fork of each of the repos at https://github.com/spender-sandbox/ which you may
submit pull requests to that I will respond to quickly.
