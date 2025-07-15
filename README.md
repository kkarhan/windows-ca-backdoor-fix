#	Windows CA Backdoor Fix*

Fixes a critical backdoor in Windows' CryptoAPI, which allows to unconsenting Update of CA Certificates in the background. 
- See [c't 17/2013 article](https://web.archive.org/web/20160507122657/https://www.heise.de/ct/ausgabe/2013-17-Zweifelhafte-Updates-gefaehrden-SSL-Verschluesselung-2317589.html) [(excerpt)](https://web.archive.org/web/20250112132700/https://www.heise.de/news/Windows-Dynamische-Zertifikat-Updates-gefaehrden-SSL-Verschluesselung-1925115.html) (both in German).
- And the applicable [research paper](https://web.archive.org/web/20120227105047/http://files.cloudprivacy.net/ssl-mitm.pdf) by Christopher Soghoian and Sid Stamm.

OFC [Microsoft claims](https://web.archive.org/web/20130803093444/http://blogs.technet.com/b/microsoft_presse/archive/2013/07/31/microsoft-statement-zu-medienberichten-wie-windows-hintert-252-r-gef-228-hrdet-internetverschl-252-sselung.aspx) this is *not a backdoor*.
- Given past and present intransparency as well as [legislation](https://en.wikipedia.org/wiki/CLOUD_Act) that prevents them from being honest, I'd be doubtful about that.

##	Useage
###	Just execute [the registry file](ms-ca-backdoor-fix.reg) with admin rights.
If you don't trust me, just check it with virustotal or any other tool of choice...
- Only 1/67 reported not clean. 
  - The 1 that did only looked at the file extension...
  -	See report here: https://www.virustotal.com/#/url/50ce5a7a9acb5bdce49d3f33c871f06d04a2b09a6751babbaced6daa2c627c72/detection

## Why Fix with a * ?
###	Because the *correct solution* is to get rid of Windows entirely!
Consider looking at [EndOf10](https://endof10.org) and [AlternativeTo](https://alternativeto.net/software/windows-11/?feature=operating-system) for proper alternatives to a Govware as Operating System.

