### Concreate5 CMS Scan

#### Shodan
1. Set-Token: Concreate5

#### One-liner
1. Shodan Search "Set-Cookie: Concreate5" --fields ip_str,port --sparator " " | awk '{print $1':'$2}' | tee -a shodan-concreate-ips.txt | httpx --silent

#### Use Nuclei Template
1. cat shodan-concreate5-ips.txt | httpx --silent | nuclei -t concreate.yml

