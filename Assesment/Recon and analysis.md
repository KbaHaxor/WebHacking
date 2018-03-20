# Information Gathering
- [ ] Automated discovery
- [ ] Harvesting public information
- [ ] Manual application discovery

### Automated discovery


##### 1\. Sublist3r - Scanning for subdomains or [Sublist3r on multiply domains](https://github.com/Zawadidone/WebHacking/tree/master/Resources/Cheatsheet)
```
sublist3r -d <domain>
```


##### 2\. Nmap - dns brute
Bruteforce domain for subdomains
```
nmap --script dns-brute <domain>
```


##### 3\. Striker - Offensive information and vulnerability scanner
Scanning for services running on ports and other vhosts
```
cd Striker && python striker.py
```


### [Subdomaintakover](https://github.com/Zawadidone/WebHacking/blob/master/Resources/Subdomaintakeover.md)


##### 1\.  - 
```
```


### Harvesting public information


##### 1\. Shodan - The search engine for Internet of Shit
Search for ip addresses associate with the company

Go to [Shodan](https://www.shodan.io/) -> Insert company name or domain -> Search -> Results :)


### Target specifiec 


##### 1\. Burpsuite - Proxy tool
Spider, scan, discover content and ....

[Burpsuite](https://github.com/Zawadidone/WebHacking/blob/master/BurpSuite/README.md)


##### 2\. Nmap Vulners - NSE script based on Vulners.com API 
Scanning for services running on ports and comparing with the vulners database(cve's)
```
nmap  -sV  --script vulners <domain>
```


##### 3\. Nikto - Web server scanner
Scan for configurations ...
```
nikto -h <domain> -C all
```


##### 4\. Dirb - Domain Brute-forcing Tool
Bruteforce directories
```
dirb <url> -f
```


##### Others

![Recon](https://github.com/Zawadidone/WebHacking/blob/master/images/Recon.jpg?raw=true)
