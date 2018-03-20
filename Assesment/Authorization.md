# Authorization

- [ ] Insecure authorization design
- [ ] Only client side authorization
- [ ] Variable manipulation
- [ ] Direct access to resources
- [ ] IDOR


### IDOR - [OWASP](https://www.owasp.org/index.php/Testing_for_Insecure_Direct_Object_References_(OTG-AUTHZ-004))
Burpsuite Comparer - Compare request with 2 accounts

Create 2 accounts, change profile settings and compare every request to this with a lot of features in the application
```
Proxy -> Intercept -> Click on(Intercept is off) -> Do the action -> Right-click on Send to comparer
```
