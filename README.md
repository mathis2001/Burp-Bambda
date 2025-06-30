Simple list of custom bambdas for "custom actions" and proxy history filtering

# How to import

1. Download the scripts

```
git clone https://github.com/mathis2001/Burp-Bambda
```

2. Open Burp,
3. Go to **"Extension"**,
4. Go to **"Bambda Library"**,
5. Click on **"Import"**,
6. Import the scripts.

# Scripts usage

## Access-Controls-Testing.bambda

Allows you to define a list of (bearer) tokens for different roles/users of the application and repeat the original request with each of them.
Then it return the status code and the body of the responses.

### Screenshot

![BAC-testing](https://github.com/user-attachments/assets/432d6bd0-862b-4494-9bc7-13541672e235)

## AuthorizationMethodTests.bambda

Repeat the original request with different Authorization methods (Basic, Bearer and NTLMSSP) and values to check how they are handled.

### Screenshot

[ToDo]

## HTTP-Methods-Fuzzing.bambda

Repeat the original request with a list of HTTP methods and return the status code and body of the request.

### Screenshot

![Http-methods](https://github.com/user-attachments/assets/d0a0afc3-4477-4bba-b28e-e8ee3b1e14aa)

## IP-Spooding-Tests.bambda

Repeat the request with HTTP headers often used to spoof the client IP like X-Client-IP, X-Forwarded-For etc to check for IP restriction bypasses.

### Screenshot

[ToDo]

## JS-Functions-Analysis.bambda

Highlight HTTP responses containing potentially dangerous JS Functions in the HTTP history

### Screenshot

[ToDo]

## ParamHighlighter.bambda

Highlight HTTP requests containing parameters that are often vulnerable to SSRF (Yellow), SQLi (Red), XSS (Blue), LFI (Orange), Open Redirect (Green) and RCE (White)

### Screenshot

[ToDo]
