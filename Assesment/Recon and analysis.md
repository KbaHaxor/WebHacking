# Information Gathering
- [ ] Manual application discovery
- [ ] Automated discovery
- [ ] Harvesting public information

### Subdomain Discovery for choosing a target


##### 1\. Sublist3r - Scanning for subdomains
```
sublist3r -d <domain>
```


##### 2\. Striker - Offensive information and vulnerability scanner
Scanning for services running on ports and other vhosts
```
striker
```

##### 3\. Shodan - The search engine for Internet of Shit
Search for ip addresses associate with the company

Go to [Shodan](https://www.shodan.io/) -> Insert company name or domain -> Search -> Results :)


### Target specifiec 


##### 1\. Burpsuite - Proxy tool
Spider, scan, discover content and ....

[Burpsuite](https://github.com/Zawadidone/WebHacking/blob/master/BurpSuite/README.md)

##### 2\. Nmap Vulners - NSE script based on Vulners.com API 
Scanning for services running on ports 
```
nmap -p-  -sV  --script vulners <domain>
```


##### 3\. Nikto - Web server scanner
Scan for configurations ...
```
nikto -h <domain> -C all
```


##### Others

![Recon](https://github.com/Zawadidone/WebHacking/blob/master/images/Recon.jpg?raw=true)
