# security-stuff
A collection of links and useful security stuff

## Misc
### regexp for finding secrets in burp history
```
(?i)((access_key|access_token|admin_pass|admin_user|algolia_admin_key|algolia_api_key|alias_pass|alicloud_access_key|amazon_secret_access_key|amazonaws|ansible_vault_password|aos_key|api_key|api_key_secret|api_key_sid|api_secret|api.googlemaps AIza|apidocs|apikey|apiSecret|app_debug|app_id|app_key|app_log_level|app_secret|appkey|appkeysecret|application_key|appsecret|appspot|auth_token|authorizationToken|authsecret|aws_access|aws_access_key_id|aws_bucket|aws_key|aws_secret|aws_secret_key|aws_token|AWSSecretKey|b2_app_key|bashrc password|bintray_apikey|bintray_gpg_password|bintray_key|bintraykey|bluemix_api_key|bluemix_pass|browserstack_access_key|bucket_password|bucketeer_aws_access_key_id|bucketeer_aws_secret_access_key|built_branch_deploy_key|bx_password|cache_driver|cache_s3_secret_key|cattle_access_key|cattle_secret_key|certificate_password|ci_deploy_password|client_secret|client_zpk_secret_key|clojars_password|cloud_api_key|cloud_watch_aws_access_key|cloudant_password|cloudflare_api_key|cloudflare_auth_key|cloudinary_api_secret|cloudinary_name|codecov_token|config|conn.login|connectionstring|consumer_key|consumer_secret|credentials|cypress_record_key|database_password|database_schema_test|datadog_api_key|datadog_app_key|db_password|db_server|db_username|dbpasswd|dbpassword|dbuser|deploy_password|digitalocean_ssh_key_body|digitalocean_ssh_key_ids|docker_hub_password|docker_key|docker_pass|docker_passwd|docker_password|dockerhub_password|dockerhubpassword|dot-files|dotfiles|droplet_travis_password|dynamoaccesskeyid|dynamosecretaccesskey|elastica_host|elastica_port|elasticsearch_password|encryption_key|encryption_password|env.heroku_api_key|env.sonatype_password|eureka.awssecretkey)[a-z0-9_ .\-,]{0,25})(=|>|:=|\|\|:|<=|=>|:).{0,5}['\"]([0-9a-zA-Z\-_=]{8,64})['\"]
```
### Current Burp Extensions
- [Burp JS Miner](https://github.com/PortSwigger/js-miner)
- [Autorize](https://github.com/portswigger/autorize)
- [Active Scan++](https://github.com/portswigger/active-scan-plus-plus)
- [Backslash powered scanner](https://github.com/portswigger/backslash-powered-scanner)
- [Param Miner](https://github.com/portswigger/param-miner)
- [Collaborator Everywhere](https://github.com/portswigger/collaborator-everywhere)
- [JSON Web Tokens](https://github.com/portswigger/json-web-tokens)
- [InQL](https://github.com/portswigger/inql)
- [HTTP Request Smuggler](https://github.com/portswigger/http-request-smuggler)
- [Upload Scanner](https://github.com/portswigger/upload-scanner)
- [CO2](https://github.com/portswigger/co2)
- [J2EEScan](https://github.com/portswigger/j2ee-scan)
- [JS Link Finder](https://github.com/portswigger/js-link-finder)
- [Logger++](https://github.com/portswigger/logger-plus-plus)
- [GAP](https://github.com/portswigger/get-all-parameters)
- [Distribute Damage](https://github.com/portswigger/distribute-damage)
- [IIS Tilde Enumeration Scanner](https://github.com/portswigger/iis-tilde-enumeration-scanner)
- [Look Over There](https://github.com/portswigger/look-over-there)
- [Software Vulnerability Scanner](https://github.com/portswigger/software-vulnerability-scanner)
- [SAML Raider](https://github.com/portswigger/saml-raider)
- [Encode IP](https://github.com/portswigger/encode-ip)

### Environment setup
- [Kitty](https://sw.kovidgoyal.net/kitty)
- [SketchyBar](https://github.com/FelixKratz/SketchyBar)
- [pipx](https://pipx.pypa.io/stable/)
- [Stow](https://www.youtube.com/watch?v=y6XCebnB9gs)

## Application security
### Content Discovery
- https://github.com/iamj0ker/bypass-403 - A simple script to test for 403 bypasses
- https://github.com/Dheerajmadhukar/4-ZERO-3 - Tool to bypass 403/401
- https://github.com/xnl-h4ck3r/waymore - Get URLs from different archive providers

### Injections
#### XSS
##### WAF/Filter bypass
- https://gist.github.com/0xSojalSec/461bccca9fc927ea2de39943178ca3eb - Mutations in anchor tags

#### CSS Injection
 - https://portswigger.net/research/blind-css-exfiltration - Blind data exfiltration with CSS
#### SQLi
- https://www.imperva.com/blog/how-to-exploit-sql-server-using-ole-automation - Exploiting SQL Server OLE Automation

### Code Analysis
- https://github.com/noir-cr/noir - Attack surface detector that identifies endpoints by static analysis
- https://github.com/Liodeus/swaggerHole - Tool for retrieving secrets in the public APIs on swaggerHub.

## Wordlists
- https://github.com/Ademking/repolist - Generate Wordlists from GitHub Repositories
- https://github.com/assetnote/wordlists - Updated wordlists

## Misc
 - https://chat.openai.com/g/g-HTsfg2w2z-secgpt - Jason Haddix´s GPT. Must be good stuff.
 - https://github.com/pentestmuse-ai/PentestMuse - An AI pentest assistant
 - https://github.com/fr0gger/Awesome-GPT-Agents - Awesome GPTs (Agents) for Cybersecurity
 - https://github.com/stolenusername/cowitness - a tool designed to function as an HTTP, HTTPS, and DNS server. It allows you to serve web pages, log HTTP requests, and customize DNS responses

 ## Blue Team
 - https://medium.com/palantir/restricting-smb-based-lateral-movement-in-a-windows-environment-ed033b888721 Restricting SMB-based Lateral Movement in a Windows Environment
- https://medium.com/palantir/windows-privilege-abuse-auditing-detection-and-defense-3078a403d74e - Windows Privilege Abuse: Auditing, Detection, and Defense
- https://medium.com/@kurmiashish/s3insights-58f24046cde3 - Monitor S3
- https://www.trustedsec.com/blog/4-free-easy-wins-that-make-red-teams-harder/ - 4 Free Easy Wins That Make Red Teams Harder

## Human stuff
- https://github.com/tadwhitaker/Security_Architect_and_Principal_Security_Engineer_Interview_Questions - Interview questions for security professionals
- https://alexw.substack.com/p/hire - Interview questions for security professionals
- https://github.com/liuchong/awesome-roadmaps - Roadmaps for learning stuff
- https://www.julian.com/guide/write/intro - Write better

### Material for talks
- https://www.bleepingcomputer.com/news/security/meet-the-unique-new-hacking-group-alphalock - New business model for Russian cybercriminals
 - https://citizenlab.ca/2020/12/the-great-ipwn-journalists-hacked-with-suspected-nso-group-imessage-zero-click-exploit/ - Journalists hacked using Pegasus spyware
 - https://www.netspi.com/blog/executive/penetration-testing/four-ways-pentesting-is-shifting-to-an-always-on-approach/ - Penetration-testing-as-a-service model
 - https://www.theregister.com/2021/02/18/cve_exploitation_2_6pc_kenna_security - Just 2.6% of 2019's 18,000 tracked vulnerabilities were actively exploited in the wild
 - https://www.trustedsec.com/blog/4-free-easy-wins-that-make-red-teams-harder/ - 4 Free Easy Wins That Make Red Teams Harder

