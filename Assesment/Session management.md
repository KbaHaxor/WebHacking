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


##### 1\. [Analyze cookies with the Burpsuite Sequencer](https://github.com/Zawadidone/WebHacking/blob/master/BurpSuite/Tools/Sequencer.md)


##### 2\. [SSL Server test](https://www.ssllabs.com/ssltest/)


##### 3\. HSTS - Strict Transport Security
Check HSTS header
```
curl -s -D- <domain> | grep -i Strict  
```

##### 4\. Burpsuite CSRF scanner
Check CSRF in Burpsuite sitemap
