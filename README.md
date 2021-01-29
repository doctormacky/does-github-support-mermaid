# does-github-support-mermaid
```sequence
    WebUI->Next Gen Auth: Login with ibm sso code
    Next Gen Auth->IBM SSO: Retrospect with sso code
    IBM SSO-->Next Gen Auth: Return jwt information
    Next Gen Auth->>Next Gen Auth: Check if the user is in whitelist
    Next Gen Auth-->WebUI: Return the username, email.
```
