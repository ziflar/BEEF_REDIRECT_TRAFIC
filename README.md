# BEEF_REDIRECT_TRAFIC
# HTTP Injector

The builtin "Match and Replace" feature applies a simple regexp to every request/response
No way to 1) restrict to scope 2) do complex filtering 3) target specific IP addresses
# This extension allows to inject some JavaScript if:
- the client wasn't already infected (3 ways to manage duplicates)
- the page URL is in scope (or not)
- the response body matches a specific string
- the response has the desired MIME type
- The target is usually externally MITM-ed via ARP, DNS or WPAD attacks
# Use cases:
- load a client side-side attack in an iframe (like Metasploit Browser AutoPwn)
- inject BeEF hooks
- load Firebug Lite in a mobile browser like iPad and iPhone
- add a <img> tag pointing to a SMB share in order to capture NTLM hashes
