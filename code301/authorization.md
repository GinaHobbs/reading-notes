# What is OAuth

1. What is OAuth?
```
OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.
```

2. Give an example of what using OAuth would look like.
```
The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon.
```

3. How does OAuth work? What are the steps that it takes to authenticate the user?
```
1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
1. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
3. The first site gives this token and secret to the initiating user’s client software.
4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
6. The user approves (or their software silently approves) a particular transaction type at the first website.
7. The user is given an approved access token (notice it’s no longer a request token).
8. The user gives the approved access token to the first website.
9. The first website gives the access token to the second website as proof of authentication on behalf of the user.
10. The second website lets the first website access their site on behalf of the user.
11. The user sees a successfully completed transaction occurring.
OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).
```

4. What is OpenID?
```
...rather than having multiple logins for multiple websites, OpenID would serve as a single sign-in, vouching for the identities of users
```

# Authorization and Authentication flows

1. What is the difference between authorization and authentication?
Authentication prompts the user for a password to access services and authorization means the user has the level of access required to use services.

2. What is Authorization Code Flow?

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

4. What is Implicit Flow with Form Post?
Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates.

5. What is Client Credentials Flow?
Instead, M2M apps use the Client Credentials Flow (defined in OAuth 2.0 RFC 6749, section 4.4), in which they pass along their Client ID and Client Secret to authenticate themselves and get a token.
```
The client can request an access token using only its client
credentials (or other supported means of authentication) when the
client is requesting access to the protected resources under its
control, or those of another resource owner that have been previously
arranged with the authorization server (the method of which is beyondthe scope of this specification).
```

6. What is Device Authorization Flow?
With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device.

7. What is Resource Owner Password Flow?
Though we do not recommend it, highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials (username and password), typically using an interactive form.