# Session management

- [ ] Session fixation
- [ ] Weak session token quality 
- [ ] Weak session token management 
- [ ] Weak logout
- [ ] Cross-site request forgery
- [ ] Weak CORS
- [ ] Session token protection
- [ ] No session timeout
- [ ] Session encryption (SSL/TLS)


### Session fixation & Weak session token quality & Weak session token management
[Analyze cookies with the Burpsuite Sequencer](https://github.com/Zawadidone/WebHacking/blob/master/BurpSuite/Tools/Sequencer.md)

### Weak logout
Logout of the account and follow the request with the Burpsuite proxy
```
Proxy -> Intercept -> Click on(Intercept is off) -> Logout and follow requests
```

### Cross-site request forgery
Check CSRF in Burpsuite sitemap

###  Session encryption (SSL/TLS)

##### 1\. [SSL Server test](
https://www.ssllabs.com/ssltest/)


##### 2\. HSTS - Strict Transport Security
Check HSTS header
```
curl -s -D- <domain> | grep -i Strict  
```
