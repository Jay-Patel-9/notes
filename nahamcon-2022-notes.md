# Content Discovery by JHaddix:
```
	-> Scanning
		- Naabu - Port
		- Nuclei
	-> Tools
		- Feroxbuster.
		- ffuf
		- gobuster
	-> Wordlist:
		- raft
		- wordlist.assetnote.com
		- Jhaddix all_content_wordlist.
		-> Technology wise wordlist
			- AEM,APACHE, CHERRPY CLOUDFUSION, DJANGO, EXPRESS, FLASK, LARAVEL ETC.
	-> Special Attention to
		- config files for db connection
		- Where the admin logins and routes/endpoints are.
	-> Check github: 
		- danielmiessler/Source2URL
		- ameenmaali/wordlistgen
		- michael1026/trashcompactor
			> echo bugcrowd.com | gau | wordlistgen | sort -u
		- dwisiswant0/apkleaks
	-> Burp Scavenger:- Create wordlists out of the burp history.
	-> GAU
	-> NEver give up - if you get 401 , try to do recursive bruteforce on it.
		- https://app.com/admin/ - 401
		- https://app.com/admin/dashboard - 401
		- https://app.com/admin/dashboard/members - 200 
	-> ## Spidering
		- Gospider
		- Hackcrawler
	- Javascript Parsing:
		- Linkfinder
		- xnLinkfinder by @Xnl-h4ck3r
		- BURP EXTENDER:- GAP (Parses both parameters & path)
	- Parameter analysis:
		- xssed.com
		- burp/conf/issues.json
		- jhaddix/sus_params -> Keep wathcing it for release.
	- Burp bounty pro extension
```

# Report writing:
```
	- Start from zero.
	- TLDR, Quick overview helps.
	- Write small clear short steps avoid using paragraphs.
	- Always add PoC.
	- Video PoC:
		- Make sure it's not boring. Make it short and clear.
		- Ensure video quality is high.
		- Make sure video is private.	
			- Add it to vimeo and share link/password.
	- add details of roles/permission.
	- Impact:
		- Remotly expolitable
		- Authenticated or not?
		- GDPR risk?
			- PII Leaks
		- Required any specific browser? any specific version?
		- required phishing link?
		- Include attack scenario.
	- Bug bounty:
		- Deep dive apporach
			- Maual
			- Priv escalation
		- Recon & Automation
			- Subdomain takover
			- CVE based
	- 


```

# WASM Reversing
```
	- WEB ASSEMBLY REVERSE ENGINEERING
	- 
	- 
```
# Code review by Grzegorz Niedziela (BBRE)
```
	-> Where to look for code?
		- Dockerhub
		- Via RCE/XXE/LFI
		- Cloud market place
		- Contact Sales for trial
		- Freelancing websites
	-> how to do source code analysis by Shubham shah
	-> Parts:
		- Static code analysis
		- Run the app and check the functionality
		- Debug the application/functionality
	-> SSRF case:
		- Strip server <-> Smoke Server <-> Public Users 
			- Smoke server blocks internal urls to prevent SSRF.
				- Identify the entry point/app_router and debug there.
	- lgtm.com & semgrep
	- ;
```

# Finding 0days in enterprise applications
```
# TODO
```
