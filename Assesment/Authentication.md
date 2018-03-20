# Authentication


- [ ] Password strength enforcement
- [ ] Authentication bypass
- [ ] Unauthenticated URL access
- [ ] Password brute force
- [ ] Default account(admin)
- [ ] Reset password link


###  Password strength enforcement
Check password rules(length and characters) 
```
Register a new account and use a easy password
```


### Password brute force & Default account(admin)
Use admin as username and check if website stops after multiply requests
```
Proxy -> Intercept -> Click on(Intercept is off) -> Do the action -> Right-click on Send to Intruder -> Click on Intruder and do your stuff!
```

### Reset password link

##### [Blog](https://medium.com/@logicbomb_1/bugbounty-how-i-was-able-to-compromise-any-user-account-via-reset-password-functionality-a11bb5f863b3)


##### Burpsuite Comparer - Compare request with 2 accounts
Create 2 accounts
```
Proxy -> Intercept -> Click on(Intercept is off) -> Do the action -> Right-click on Send to comparer -? Compare :)
```
